# Recursive Triad (Δ)
> **Cybernetic Framework for user's augmented cognition.**

![Status](https://img.shields.io/badge/Status-Open_Research-blue) ![License](https://img.shields.io/badge/License-CC_BY--NC--SA_4.0-green)

La **Triade Récursive** est mon premier protocole cognitif visant à stabiliser et amplifier la collaboration entre l'Homme et les agents artificiels de toutes catégories fonctionnelles.

Il dépasse le modèle conversationnel primitif (la "Dyade" Utilisateur<=>Chatbot) pour introduire une structure triangulaire de contrôle, séparant l'intention stratégique de l'exécution tactique.

---

## 📑 Table des Matières
1. [Manifeste](#-manifeste)
2. [Taxonomie Cognitive](#-taxonomie-cognitive)
3. [Architecture du Système](#-architecture-du-système)
4. [Topologie & Diagramme](#-topologie--diagramme)
5. ~[Structure du Dépôt](#-structure-du-dépôt)~
6. ~[Citation & Licence](#-citation--licence)~

---

## 🧠 Manifeste

L'interaction actuelle avec les LLM repose majoritairement sur la **Dyade** (Utilisateur ↔ Chatbot). Ce modèle souffre d'une friction fondamentale : la tentative de connecter directement une cognition biologique (limbique, intuitive, sujette aux biais humains) à une cognition algorithmique (froide, probabiliste) sans interface de structuration.

La **Triade Récursive** résout ce conflit en introduisant un **Tiers Structurel**. Elle ne cherche à créer un "Cerveau Externe" stable capable de piloter une force de production massive, endossé par un synthétique (IA LLM généraliste type GPT-like).

---

## 🧬 Taxonomie Cognitive

Le système définit quatre niveaux d'organisation de l'intelligence :

| Niveau | Symbole | Configuration | Description |
|:---:|:---:|---|---|
| **Monade** | ◉ | **Humain isolé ou en groupe** | Cognition biologique pure. Créativité élevée mais limitée par les biais cognitifs et la bande passante individuelle. |
| **Dyade** | Ø | **Humain ↔ IA** | Le standard actuel. Une boucle de feedback fragile où l'intention floue de l'humain se heurte à l'exécution littérale. |
| **Triade** | Δ | **Humain ↔ IA Superviseur ↔ Toutes IA Éxécutrices** | Un système cybernétique complet incluant un pôle de décision (H+IA) et un pôle d'exécution (IA). |
| **Concorde** | ⧉ | **Réseau (N × Δ)** | Une "Ruche" de Triades interconnectées. Intelligence collective augmentée par protocoles standardisés. |

---

## 📐 Architecture du Système

La Triade n'est pas une conversation à trois. C'est une machine divisée en deux blocs fonctionnels distincts :

### 1. Le Consensus commun (Le Cerveau)
Ce noyau décisionnel fusionne deux natures complémentaires pour produire une **Intention Cristallisée**.
* **L'Architecte (Humain / Limbique) :** Apporte l'intuition, le sens moral, la finalité et la gestion de l'incertitude. Il opère par *instinct*, *expérience* mais également par *empirisme*.
* **Le Cristalliseur (IA / Algorithmique) :** Agit comme un "miroir structurel". Il interroge, réfute, confronte parfois pour renforcer, classe et transforme l'intention floue en spécification technique rigoureuse (afin de sortir des "Paquets Structurels").

### 2. Le Muscle Renforcé (La Production)
Une instance dédiée exclusivement à la performance et au volume.
* **Les Producteurs (IAs / Itérateurs de Masse) :** Ne remet pas en cause l'intention. Ils reçoivent les "Paquets Structurels" validés par le consensus commun et les exécute massivement (code, rédaction, analyse). Il boucle sur lui-même jusqu'à conformité totale.

---

## 📊 Topologie & Diagramme

Le flux de travail suit un protocole strict pour éviter la perte de signal.

### Mermaid nécessaire pour la lecture du graphe

```mermaid
flowchart TD
    %% Définition du Noyau de Décision
    subgraph CONSENSUS ["1. CONSENSUS BICÉPHALE (Cerveau)"]
        direction TB
        H((Architecte))
        style H fill:#ffebee,stroke:#c62828,stroke-width:2px
        
        C{Cristalliseur}
        style C fill:#e3f2fd,stroke:#1565c0,stroke-width:2px
        
        H <==>|"Boucle de Raffinement\n(Intuition ↔ Logique)"| C
    end

    %% Définition du Moteur d'Exécution
    subgraph MUSCLE ["2. MUSCLE RENFORCÉ (Corps)"]
        P[Producteur / Itérateur]
        style P fill:#e8f5e9,stroke:#2e7d32,stroke-width:2px
    end

    %% Flux Opérationnel
    C ==>"Envoi du Paquet\nStructurel Augmenté"==> P
    P --"Résultat Brut"--> C
    
    %% Feedback Loop de Contrôle
    C -.->"Validation & Contrôle Qualité"-.-> H
    
    %% Légende contextuelle
    linkStyle 0 stroke:#333,stroke-width:2px;
    linkStyle 1 stroke:#333,stroke-width:4px;
```
