// --------------------------------------------
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

link:#workshop[Openshift Workshop 4.3]

link:#conclusion[Conclusion]

'''

## Objectif initial 
{ref}objectifinitial{end-ref}

Apprendre à utiliser et à opérer la plateforme d'Openshift

{reftoc}

'''

{ref}contexte{end-ref}  

## Hypothèse

* Infrastructure Infonuagique: AWS
* Système d'exploitation: Red Hat 7
* PaaS: Openshift 4.3
* Poste(s) de travail : Windows Serveur 2008, Windows 10, Ubuntu 18.04

{reftoc}

'''

{ref}iteration{end-ref}

#### Objectifs

* Réaliser une expérimentation de développement moderne dans le contexte du dossier d’opportunité d’industrialisation des écosystèmes de développement.
* Apprendre à exploiter Openshift
* Apprendre à exploiter les outils de l'intégration continue et de déploiement continu
* Documenter les expériences et réalisations
* Déployer la plateforme en tant que service (PaaS) sur plusieurs cloud : RedHat Openshift, Container Ready (localement)
* Expérimenter le IaaS via les services de Microsoft Azure et AWS
* Expérimenter le concept DevOps

#### Réalisations

* Installation d'OpenShift sur avec CodeReady localement
* Chaque membnre du noyau a réaliser les travaux pratique d'OpenShift 4.3
* Installation des outils Ansible sur un poste de travail linux
* Génération de clés SSH via Windows ou Linux
* Création et exécution de playbooks Ansible
* Découvertes/Apprentissages sur la configuration d'un déploiement d'applications sur la plateforme (Jenkins, SonarQube, Artifactory, ...)
* Documentation des expériences et réalisations
* Utilisation de la documentation avec la technique Markdown(.md) et ASCIIdoc (.adoc)
* Familiarisation avec les 12 facteurs permettant à une application d'être qualifié "Cloud native" (12 factors apps) (https://12factor.net/fr/)

{reftoc}

'''

{ref}workshop{end-ref}

## Openshift Workshop 4.3