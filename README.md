﻿// --------------------------------------------
// Définition des attributs du document
// --------------------------------------------

// < Chemins relatifs >
:path-lab: ../
:path-exp: {path-lab}Exp004-a/
:path-images: {path-exp}images/
:imagesdir: {path-lab}images/

// < Raccourci: Saut de ligne>
:bl: pass:[ +]

// < Raccourci: ToC>
:deftoc: pass:[<a name="ToC"></a>]
:reftoc: pass:[link:#ToC[Table des matières]]

// < Raccourci: Signet>
//Signet
:ref: pass:[<a name="]
:end-ref: pass:["></a>]


//--------------------------------------------

# Laboratoire PaaS

'''

{deftoc}

## Table des matières

link:#objectifinitial[Objectif initial]

link:#contexte[Contexte]

link:#iteration[Itérations]

link:#methode[Méthode d'évaluation]

link:#workshop[Openshift Workshop 3.11]

link:#conclusion[Conclusion]

'''

## Objectif initial 
{ref}objectifinitial{end-ref}

Apprendre à utiliser et à opérer la plateforme d'Openshift

{reftoc}

'''

{ref}contexte{end-ref}  

## Contexte

DO - Industrialisation de l'écosystème de développement

## Hypothèse

image::Azure_OpenShift_gouv.png[Architecture Microsoft Azure]

* Infrastructure Infonuagique: Azure
* Système d'exploitation: Red Hat 7
* PaaS: Openshift 3.11
* Poste(s) de travail : Windows Serveur 2008, Windows 8.1, Ubuntu 18.04

{reftoc}

'''

{ref}iteration{end-ref}

## Itérations

### Itération 1 (mai-juin)

#### Affectations

* 2 personne à 4j/semaine
* 1 personne à 4j/semaine
* 2 personnes à 1j/ semaine

#### Objectifs

* Réaliser une expérimentation de développement moderne dans le contexte du dossier d’opportunité d’industrialisation des écosystèmes de développement.
* Apprendre à exploiter Openshift
* Apprendre à exploiter les outils de l'intégtation continue et de déploiement continu
* Documenter les expériences et réalisations
* Déployer la plateforme en tant que service (PaaS) sur plusieurs cloud : RedHat Openshift
* Expérimenter le IaaS via les services de Microsoft Azure et AWS
* Expérimenter le concept DevOps

#### Hypothèses

* Déploiement en quelques heures avec l'aide des ressources de RedHat
* Réalisation rapide des laboratoires proposés (3 à 5 j/p)
* Création rapide d'une coquille d'application et de son pipeline de développement

#### Réalisations

* Installation d'OpenShif sur Azure via le marketplace
* Chaque membnre du noyau a réaliser les travaux pratique d'OpenShift 3.11 [Openshift Workshop v3](https://gitlab.forge.gouv.qc.ca/dsoc/openshiftv3-workshop)
* Installation des outils Ansible sur un poste de travail linux
* Installation d'OpenShif sur Azure via des playbook Ansible [Openshift Install Playbook](https://gitlab.forge.gouv.qc.ca/dsoc/openshiftinstallplaybook), [Openshift Azure](https://gitlab.forge.gouv.qc.ca/dsoc/Openshift_Azure)
* Génération de clés SSH via Windows ou Linux
* Création et exécution de playbooks Ansible
* Découvertes/Apprentissages sur la configuration d'un déploiement d'applications sur la plateforme (Jenkins, SonarQube, Artifactory, ...)
* Documentation des expériences et réalisations
* Utilisation de la documentation avec la technique Markdown(.md) et ASCIIdoc (.adoc)
* Familiarisation avec les 12 facteurs permettant à une application d'être qualifié "Cloud native" (12 factors apps)

#### Constats

* Temps 1ere installation 2 jours
* La commande ```oc delete projects --all``` avec le compte ```clusteradmin``` supprime tous les projets accessibles dont ceux qui soutiennent la plateforme
* Le temps réinstallation pas à pas avec Ansible 1 semaine
* Certains travaux pratiques contenait des commandes erronés avec la version 3.11 ce qui a causé quelques problèmes
* Courbe d'apprentissage de la plateforme plus élevée que prévue (commandes consoles, configurations json,yaml, outil client (oc), ...)
* Autonomie à développer
* Le renouvellement d'un abonnement d'évaluation dans Microsoft Azure est impossible et limites les actions avec les ressources actives après qu'il est échu.
* Lorsque les licences de RedHat sont échus, la limite est seulement au niveau du support et des mises à jour
* 

{reftoc}

'''

{ref}workshop{end-ref}

## Openshift Workshop 4.3