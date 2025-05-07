 `README.md` :



# 🖥️ Module Odoo – Gestion de Parc Informatique (Infogérance)

## 📌 Contexte

Ce projet consiste à développer un module complet dans Odoo 18.0 pour la gestion de parcs informatiques, destiné aux prestataires de services IT. Le module permet de gérer les équipements (ordinateurs, imprimantes, routeurs, caméras, etc.), les licences logicielles, les interventions techniques, la facturation récurrente et le portail client. Il s’inspire de l’outil GLPI, mais avec l’intégration complète dans l’environnement Odoo (comptabilité, RH, stock, portail).

## 🎯 Objectifs

* Suivi des équipements informatiques mis à disposition des clients
* Gestion des incidents et des interventions (curatives et préventives)
* Suivi des contrats de service (maintenance, licences)
* Facturation automatique des prestations via abonnements
* Interface portail pour les clients (consultation du parc, tickets, factures)
* Support multi-sociétés avec isolation des données entre clients

## 🧱 Fonctions principales

### 1. Gestion de Parc

* Création et suivi d’équipements par client
* Gestion des garanties, affectation utilisateurs, alertes automatiques
* Suivi des licences et logiciels (dates d’expiration, clés)
* Intégration avec le stock (consommables, pièces détachées)

### 2. Tickets & Interventions

* Création de tickets depuis l’interface interne ou le portail client
* Assignation aux techniciens internes
* Planification des interventions préventives ou correctives
* Suivi du temps passé, historique, pièces consommées

### 3. Contrats & Abonnements

* Création de contrats de maintenance ou de licences
* Définition des périodes et alertes de renouvellement
* Lien avec les équipements couverts
* Plans d’abonnements configurables

### 4. Facturation récurrente

* Génération automatique des factures selon les contrats
* Intégration comptable (Odoo Accounting/Invoicing)
* Suivi des paiements et relances

### 5. Portail Client

* Vue simplifiée du parc informatique (matériels et logiciels)
* Suivi des tickets ouverts et résolus
* Téléchargement des factures
* Vue des abonnements et contrats actifs

## 🛠️ Modules Odoo utilisés

* `maintenance`: équipements et calendrier d'intervention
* `helpdesk`: tickets et suivi des incidents
* `sale_subscription`: contrats et facturation périodique
* `account`: génération des factures et paiements
* `inventory`: gestion des stocks de consommables
* `portal`, `website`: portail client personnalisé
* `hr`: gestion des techniciens et des affectations
* `multi_company`: gestion multi-clients (multi-sociétés)

## 📂 Structure du module

* Gestion des équipements (matériel et logiciels)
* Incidents et interventions (tickets)
* Contrats et abonnements
* Factures et paiements
* Accès portail client sécurisé
* Paramétrage des alertes (licences, garanties, renouvellements)




