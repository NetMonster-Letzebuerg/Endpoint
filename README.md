[FR]
# Netmonster Luxembourg - Endpoint

Basé sur le systéme de Luis Baker - Netmonster Portugal

**Description simplifiée:**

NetMonster Luxembourg gère la collecte et le traitement des données de localisation des antennes mobile des quatres opérateur nationaux. Le système comprend:

**Fonctionnalité:**

1. **Mise a jour de la base de donnée réguliére:**
   - Les fichiers de mise a jours des base de donnée sont publié a intervale régulier

2. **Envoi de données de localisation:**
   - Les utilisateurs soumettent des informations depuis netmonster en formas JSON via l'endpoint.

3. **Intégration des bases de données:**
   - Facilite l'intégration dans les bases de données de chaque opérateurs.

4. **Traitement flexible:**
   - Permet un traitement personnalisé des informations.

**Information sur les contribution:**

   - Statistique quotidienne sur les contribution.
   - Enregistre les modèles de smartphones les plus utilisés par marque.

**Registo de Modelos por Operadoras:**

   - Capture et enregistre les modèles de smartphones les plus utilisés par chaque opérateur.
   - Les statistique comprends les opérateur suivant : POST, Orange LU, Tango (Proximus Luxembourg), LOL (Luxembourg Online).

**Frontend:**
   - Systéme d'affichage des statistique pour chaque opérateur.
   - Permet d'accéder aux bases de données de chaque opérateur Luxembourgeois.

[LU]

# Netmonster Lëtzebuerg - Endpoint

Baséiert op Luis Baker System - Netmonster Poutugal

**Vereinfacht Beschreiwung:**

Netmonster Lëtzebuerg geréiert d'Sammlung an d'Veraarbechtung vu Standortdaten vun den mobilen Antennen vun de véier nationalen Opérateuren. De System enthält :

**Funktionalitéit:**

1. **Reegelméissegen Datebankupdate.**
   - Datebank Update dateie ginn a reegelméissegen intervalle publizéiert

2. **Standortdaten schécken:**
   - D'Benotzer schécken informatioun vum Netmonster an JSON Formater iwwer den Endpunkt

3. **Datebankintegratioun**
   - Erliichtert d'Intergratioun an d'Datenbanken vun all Bedreiwer

4. **Bäitrag Informatiounen:**
   - Deeglech statistiken iwwer Contributiounen.
   - Spuert déi meescht benotzt Smartphone Modeller no Mark.

**Registréiert Modeller vun Operadoras:**
   - Erfaasst a registréiert déi meescht benotzt Smartphone modeller vun all bedreiwer.
   - D'Statistik enthält folgend Bedreiwer : POST, Orange LU, Tango (Proximus Lëtzebuerg), LOL (Luxembourg Online).

**Frontend:**
   - Statistik Display system fir all bedreiwer
   - Erlaabt Zougang zu den Datenbanken vun all Lëtzebuerger Bedreiwer

# Project Setup and Start Guide

## Prerequisites

Before you begin, ensure you have met the following requirements:

- You have installed the latest LTS version of [Node.js and npm](https://nodejs.org/en/download/).
- You have a Windows/Linux/Mac machine.

## Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/NetMonster_Portugal_system.git
   ```

2. Navigate to the project directory:

   ```bash
   cd NetMonster_Portugal_system
   ```

3. Install the project dependencies:

   ```bash
   npm install
   ```

## Start

To start the project, run the following command: `npm start`


## Environment Variables

The following environment variables can be configured in the project:

- `PORT`: The port number on which the server will listen. Default is `8080`.

Make sure to set these variables according to your environment before starting the project.

## Linting and formatting

This projects uses [Biome](https://biomejs.dev/guides/getting-started/) to lint and format all JavaScript files. Make sure to install the [VSCode extension](https://biomejs.dev/guides/integrate-in-editor/#vs-code) to have support for Biome while developing.

