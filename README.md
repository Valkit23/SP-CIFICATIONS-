# PROTOTYPE DE RECENSEMENT MULTISECTORIEL

**Base de données Oracle - Collecte de données statistiques**

---

## 1. OBJECTIF DU PROTOTYPE

Créer un formulaire de recensement qui permet de collecter des données statistiques auprès de la population, en couvrant **11 secteurs d'activité**.

Chaque personne recensée est identifiée par :
- Son secteur
- Sa profession
- Son âge
- Son sexe
- Son état civil
- Et d'autres attributs spécifiques à chaque secteur

---

### Classification par âge

| Catégorie | Tranche d'âge | Définition |
|-----------|---------------|------------|
| **Mineur** | 0 - 17 ans | Enfants / Adolescents |
| **Majeur** | 18 - 25 ans | Jeune adulte |
| **Adulte** | 26 - 59 ans | Adulte en activité |
| **Vieux** | 60 ans et + | Senior / Personne âgée |

---

## 2. SECTEURS COUVERTS ET LEURS SPÉCIFICITÉS

### 2.1 Infrastructures

**Utilité :** Recenser les personnes travaillant dans les infrastructures, les projets et les équipements.

**Questions spécifiques :**
- Type d'infrastructure (ponts, routes, bâtiments publics, réseaux d'eau/électricité)
- Statut du projet (en construction, en maintenance, terminé)
- Année de construction
- État actuel (bon, moyen, mauvais)
- Budget alloué
- Source de financement (État, Partenaires, Privé)

**Causes / Problèmes rencontrés :**
- Dégradation prématurée → Mauvaise qualité des matériaux, surcharge, intempéries
- Retard de livraison → Financement insuffisant, conflits fonciers, grèves
- Accidents de chantier → Manque d'équipements de sécurité, négligence humaine
- Corrosion des structures → Humidité excessive, absence d'entretien

---

### 2.2 Finance

**Utilité :** Recenser les professionnels du secteur financier, les institutions et les opérations.

**Questions spécifiques :**
- Institution financière (Banque, Assurance, Microfinance, etc.)
- Poste occupé
- Années d'expérience
- Type de services offerts
- Nombre de clients
- Volume des transactions (mensuel)
- Zone d'opération (urbain, rural, national)

**Causes / Problèmes rencontrés :**
- Non-remboursement des crédits → Chômage, mauvaise gestion, aléas climatiques
- Fraude financière → Falsification de documents, corruption, cybercriminalité
- Baisse des transactions → Inflation, instabilité politique, crise économique
- Exclusion bancaire → Manque de pièces d'identité, faible revenu

---

### 2.3 Économie

**Utilité :** Recenser les acteurs économiques, les commerçants, les entreprises et leurs activités.

**Questions spécifiques :**
- Type d'activité économique (Commerce, Agriculture, Services, Industrie)
- Taille de l'entreprise (Petite, Moyenne, Grande)
- Nombre d'employés
- Chiffre d'affaires annuel
- Secteur d'activité précis (agroalimentaire, textile, numérique, etc.)
- Zones de marché (local, national, international)

**Causes / Problèmes rencontrés :**
- Baisse des ventes → Concurrence déloyale, baisse du pouvoir d'achat
- Pénurie de matières premières → Problèmes d'approvisionnement, hausse des prix
- Fermeture d'entreprises → Mauvaise gestion, fiscalité excessive, manque de financement
- Informalité du secteur → Complexité administrative, coût des formalités

---

### 2.4 Santé

**Utilité :** Recenser l'état de santé de la population, les maladies, les traitements et les structures de santé.

**Questions spécifiques :**
- État de santé (Malade / Non malade)
- Maladie diagnostiquée
- Traitement en cours
- Date du diagnostic
- Structure de santé fréquentée (Hôpital, Clinique, Centre de santé)
- Type de couverture santé (Mutuelle, Assurance, Autre, Aucune)
- Vaccination (à jour / non à jour)

**Causes / Problèmes de santé détaillés :**

| Maladie | Causes possibles |
|---------|------------------|
| Paludisme (Malaria) | Eau stagnante, moustiques, insalubrité, absence de moustiquaire |
| Fièvre typhoïde | Eau contaminée, aliments mal lavés, hygiène insuffisante |
| Diarrhée / Choléra | Eau non potable, défécation en plein air, mains sales |
| Hypertension | Alimentation trop salée, stress, sédentarité, obésité |
| Diabète | Alimentation sucrée, manque d'exercice, hérédité |
| Paludisme grave | Absence de traitement rapide, résistance aux médicaments |
| Infections respiratoires | Pollution atmosphérique, tabagisme, poussières |
| Malnutrition | Pauvreté, insécurité alimentaire, mauvaise alimentation |
| VIH/SIDA | Non-utilisation du préservatif, transfusion sanguine, transmission mère-enfant |
| Tuberculose | Promiscuité, malnutrition, faible immunité |
| Maladies de la peau | Hygiène insuffisante, eau contaminée, allergènes |

---

### 2.5 Éducation

**Utilité :** Recenser les élèves, étudiants, enseignants et les établissements scolaires.

**Questions spécifiques :**
- Niveau d'étude (Primaire, Secondaire, Supérieur, Formation professionnelle)
- Établissement fréquenté (public/privé)
- Classe / Année d'étude
- Discipline / Filière
- Résultats scolaires (moyenne / appréciation)
- Bourses ou aides financières (oui/non)
- Matériel pédagogique disponible (oui/non)

**Causes / Problèmes rencontrés :**
- Abandon scolaire → Pauvreté, grossesse précoce, mariage forcé, travail des enfants
- Échec scolaire → Manque de matériel, classes surchargées, enseignants non formés
- Analphabétisme → Non-scolarisation, conflits armés, isolement géographique
- Manque d'enseignants → Recrutement insuffisant, départs en retraite, fuite des cerveaux
### 2.6 Démographie

**Utilité :** Recenser la population, les ménages, les naissances, les décès et les migrations.

**Questions spécifiques :**
- Taille du ménage
- Nombre d'enfants
- Nationalité
- Lieu de naissance
- Année d'arrivée dans la ville/région
- Motif de la migration (travail, études, famille, autre)

**Causes / Problèmes démographiques :**
- Fort accroissement démographique → Natalité élevée, faible planification familiale
- Migration massive vers les villes → Manque d'emploi en campagne, recherche de meilleures conditions
- Vieillissement de la population → Faible natalité, espérance de vie élevée
- Disparités de genre → Préférence pour les garçons, mariages précoces des filles

---

### 2.7 Transport

**Utilité :** Recenser les usagers des transports, les véhicules et les modes de déplacement.

**Questions spécifiques :**
- Mode de transport principal (Transport en commun, Transport urbain, Véhicule personnel, Vélo, Marche)
- Type de transport en commun (Bus, Taxi, Train, Métro, Bateau)
- Transport urbain (Bus municipal, Taxi collectif, Moto-taxi)
- Véhicule personnel (Type : Moto, Voiture, Camionnette)
- Fréquence d'utilisation (quotidien, hebdomadaire, occasionnel)
- Durée moyenne du trajet (minutes/heures)
- Coût moyen du transport par mois
- Zone de déplacement (ville, interurbain, national)

**Causes / Problèmes rencontrés :**
- Embouteillages → Croissance du parc automobile, infrastructures insuffisantes
- Accidents de la route → Excès de vitesse, alcool, mauvais état des routes, imprudence
- Coût élevé du transport → Prix du carburant, entretien des véhicules, taxes
- Insécurité dans les transports → Vols, agressions, manque d'éclairage
- Pollution automobile → Vieilles voitures, carburant de mauvaise qualité

---

### 2.8 Industrie

**Utilité :** Recenser les travailleurs de l'industrie, les usines et les productions.

**Questions spécifiques :**
- Type d'industrie (Agroalimentaire, Textile, Chimique, Métallurgique, Pharmaceutique, Énergétique)
- Poste occupé (ouvrier, technicien, ingénieur, cadre)
- Années d'expérience dans le secteur
- Type de production (matières premières, produits finis, semi-finis)
- Capacité de production (par jour/mois)
- Conditions de travail (bonnes, moyennes, difficiles)
- Équipements de protection (oui/non)

**Causes / Problèmes rencontrés :**
- Faible productivité → Machines obsolètes, panne fréquentes, absentéisme
- Pollution industrielle → Rejets chimiques, absence de filtres, normes laxistes
- Accidents du travail → Non-respect des consignes de sécurité, machines non protégées
- Conflits sociaux → Bas salaires, non-paiement des heures supplémentaires

---

### 2.9 Mine

**Utilité :** Recenser les travailleurs miniers, les sites d'extraction et la production.

**Questions spécifiques :**
- Type de mine (Cuivre, Cobalt, Or, Diamant, Charbon, Autre)
- Site d'extraction (nom, localisation)
- Poste occupé (mineur, géologue, ingénieur, superviseur)
- Années d'expérience
- Conditions de travail (souterrain / à ciel ouvert)
- Production quotidienne/mensuelle
- Risques rencontrés (effondrement, poussières, produits chimiques)
- Équipements de sécurité disponibles (oui/non)

**Causes / Problèmes rencontrés :**
- Effondrement des galeries → Mauvaise consolidation, excavation excessive
- Maladies respiratoires → Inhalation de poussières, amiante, silice
- Pollution des eaux et sols → Rejets de produits chimiques (cyanure, mercure)
- Exploitation illégale → Manque de contrôle, corruption, pauvreté des populations
- Accidents mortels → Manque d'équipements de sécurité, négligence

---

### 2.10 Environnement

**Utilité :** Recenser les acteurs de la protection de l'environnement, les défis écologiques et les initiatives.

**Questions spécifiques :**
- Type d'activité (Protection de la nature, Gestion des déchets, Énergie renouvelable, Reboisement, Sensibilisation)
- Organisation ou institution
- Zone d'intervention (urbain, rural, forêt, bord de mer)
- Problèmes environnementaux constatés (pollution, déforestation, érosion, inondations)
- Initiatives en cours
- Résultats obtenus
- Partenaires impliqués

**Causes / Problèmes environnementaux :**
- Déforestation → Coupe abusive de bois, agriculture sur brûlis, expansion urbaine
- Pollution des rivières → Rejets industriels, orpaillage, déchets ménagers
- Érosion des sols → Déforestation, mauvaises pratiques agricoles
- Inondations → Pluies torrentielles, absence de canaux d'évacuation, urbanisation anarchique
- Pollution atmosphérique → Gaz d'échappement, feux de brousse, industries

---

### 2.11 Énergie

**Utilité :** Recenser les personnes travaillant dans le secteur de l'énergie (production, distribution, énergies renouvelables, etc.) et les usages énergétiques de la population.

**Questions spécifiques :**
- Domaine d'activité (Production d'énergie, Transport/distribution, Énergie renouvelable, Efficacité énergétique, Recherche)
- Type d'énergie (Électrique, Solaire, Éolienne, Hydraulique, Biomasse, Gaz, Pétrole, Charbon)
- Poste occupé (Technicien, Ingénieur, Opérateur, Cadre, Chercheur)
- Années d'expérience dans le secteur
- Structure/Entreprise (Nom de la société ou institution)
- Zone d'opération (urbaine, rurale, nationale, transfrontalière)
- Accès à l'électricité (Oui/Non)
- Source d'énergie principale utilisée à domicile (Électricité réseau, Groupe électrogène, Panneaux solaires, Bois/charbon, Gaz)
- Consommation énergétique mensuelle (estimation en kWh ou en coût)
- Projets d'énergie en cours

**Causes / Problèmes énergétiques :**
- Coupures d'électricité fréquentes → Vétusté du réseau, faible capacité de production
- Dépendance au charbon/pétrole → Manque d'investissements dans le renouvelable
- Coût élevé de l'énergie → Monopole, taxes, importation des combustibles
- Faible accès à l'électricité en milieu rural → Éloignement, coût d'extension du réseau
- Gaspillage énergétique → Équipements obsolètes, absence de sensibilisation
## 3. STRUCTURE DU FORMULAIRE DE RECENSEMENT

### 3.1 Informations communes à TOUS les secteurs (SOCLE COMMUN)

| Champ | Type | Obligatoire | Description |
|-------|------|-------------|-------------|
| Secteur | Liste déroulante | Oui | Choix parmi les 11 secteurs |
| Nom | Texte | Oui | Nom de la personne |
| Prénom | Texte | Oui | Prénom de la personne |
| Âge | Nombre | Oui | Âge en années |
| Sexe | Liste déroulante | Oui | Masculin / Féminin |
| Classification d'âge | Calcul automatique | Oui | Mineur / Majeur / Adulte / Vieux |
| État civil | Liste déroulante | Oui | Célibataire, Marié(e), Divorcé(e), Veuf(ve), Union libre |
| Commune | Liste déroulante | Oui | Ruashi, Kampemba, Katuba, Kenya, Kamalondo, Lubumbashi, Annexe |
| Quartier | Liste déroulante | Oui | Dépend de la commune choisie |
| Profession | Texte | Oui | Profession exercée |
| Est malade | Options (Oui/Non) | Oui | État de santé général |
| Cause / Problème | Zone de texte | Si malade | Description détaillée de la cause |
| Observation | Zone de texte | Non | Commentaire libre |

---

### 3.2 Champs spécifiques par secteur

#### Secteur Transport
- Mode de transport principal (liste)
- Type de transport en commun (liste)
- Type de transport urbain (liste)
- Type de véhicule personnel (liste)
- Fréquence d'utilisation (liste)
- Durée moyenne du trajet (nombre)
- Coût mensuel (nombre)

**Causes spécifiques :** Embouteillages, accidents, coût élevé, insécurité, pollution

---

#### Secteur Santé
- Maladie (texte)
- Traitement (zone de texte)
- Date du diagnostic (date)
- Structure de santé (liste)
- Couverture santé (liste)
- Vaccination (liste)

**Causes spécifiques :** Eau stagnante, eau contaminée, insalubrité, alimentation, pollution, stress, etc.

---

#### Secteur Éducation
- Niveau d'étude (liste)
- Établissement (public/privé)
- Classe / Année
- Discipline / Filière
- Résultats scolaires (texte)
- Bourses/aides (oui/non)
- Matériel disponible (oui/non)

**Causes spécifiques :** Abandon, échec, analphabétisme, manque d'enseignants

---

#### Secteur Démographie
- Taille du ménage (nombre)
- Nombre d'enfants (nombre)
- Nationalité (texte)
- Lieu de naissance (texte)
- Année d'arrivée (nombre)
- Motif de migration (liste)

**Causes spécifiques :** Natalité élevée, migration, vieillissement, disparités de genre

---

#### Secteur Infrastructure
- Type d'infrastructure (liste)
- Statut du projet (liste)
- Année de construction (nombre)
- État actuel (liste)
- Budget alloué (nombre)
- Source de financement (liste)

**Causes spécifiques :** Dégradation, retard, accidents, corrosion

---

#### Secteur Finance
- Institution (liste)
- Poste occupé (texte)
- Années d'expérience (nombre)
- Type de services (texte)
- Nombre de clients (nombre)
- Zone d'opération (liste)

**Causes spécifiques :** Non-remboursement, fraude, baisse des transactions, exclusion bancaire

---

#### Secteur Économie
- Type d'activité (liste)
- Taille de l'entreprise (liste)
- Nombre d'employés (nombre)
- Chiffre d'affaires (nombre)
- Secteur précis (texte)
- Zones de marché (liste)

**Causes spécifiques :** Baisse des ventes, pénurie, fermeture, informalité

---

#### Secteur Industrie
- Type d'industrie (liste)
- Poste occupé (liste)
- Années d'expérience (nombre)
- Type de production (liste)
- Capacité de production (nombre)
- Conditions de travail (liste)
- Équipements de protection (oui/non)

**Causes spécifiques :** Faible productivité, pollution, accidents, conflits sociaux

---

#### Secteur Mine
- Type de mine (liste)
- Site d'extraction (texte)
- Poste occupé (liste)
- Années d'expérience (nombre)
- Conditions de travail (liste)
- Production quotidienne (nombre)
- Risques rencontrés (texte)
- Équipements de sécurité (oui/non)

**Causes spécifiques :** Effondrement, maladies respiratoires, pollution, exploitation illégale, accidents

---

#### Secteur Environnement
- Type d'activité (liste)
- Organisation (texte)
- Zone d'intervention (liste)
- Problèmes environnementaux (texte)
- Initiatives en cours (texte)
- Résultats obtenus (texte)
- Partenaires (texte)

**Causes spécifiques :** Déforestation, pollution des rivières, érosion, inondations, pollution atmosphérique

---

#### Secteur Énergie
- Domaine d'activité (liste)
- Type d'énergie (liste)
- Poste occupé (liste)
- Années d'expérience (nombre)
- Structure/Entreprise (texte)
- Zone d'opération (liste)
- Accès à l'électricité (Oui/Non)
- Source d'énergie principale à domicile (liste)
- Consommation énergétique mensuelle (nombre)
- Projets en cours (zone de texte)

**Causes spécifiques :** Coupures d'électricité, dépendance au fossile, coût élevé, faible accès rural, gaspillage

---

## 4. EXEMPLES DE DONNÉES RECUEILLIES

### Exemple 1 : Secteur Santé (Paludisme)

| Champ | Valeur |
|-------|--------|
| Secteur | Santé |
| Nom | Mbemba |
| Prénom | Marie |
| Âge | 34 ans |
| Sexe | Féminin |
| Classification | Adulte (26-59 ans) |
| État civil | Mariée |
| Commune | Ruashi |
| Quartier | Luano 1 |
| Profession | Infirmière |
| Est malade ? | Oui |
| Maladie | Paludisme |
| Cause détaillée | Eau stagnante dans la cour, absence de moustiquaire |
| Traitement | Quinine 3 jours |
| Structure de santé | Hôpital |
| Couverture santé | Mutuelle |
| Vaccination | À jour |

---

### Exemple 2 : Secteur Transport

| Champ | Valeur |
|-------|--------|
| Secteur | Transport |
| Nom | Kabila |
| Prénom | Jean |
| Âge | 42 ans |
| Sexe | Masculin |
| Classification | Adulte (26-59 ans) |
| État civil | Marié |
| Commune | Kampemba |
| Quartier | Bel-Air I |
| Profession | Chauffeur |
| Mode de transport | Transport urbain |
| Type | Taxi collectif |
| Fréquence | Quotidien |
| Durée trajet | 45 minutes |
| Coût mensuel | 150 000 FC |
| Cause détaillée | Embouteillages chroniques sur l'avenue Lumumba |
| Est malade ? | Non |

---

### Exemple 3 : Secteur Énergie

| Champ | Valeur |
|-------|--------|
| Secteur | Énergie |
| Nom | Tshibanda |
| Prénom | Paul |
| Âge | 45 ans |
| Sexe | Masculin |
| Classification | Adulte (26-59 ans) |
| État civil | Marié |
| Commune | Katuba |
| Quartier | Musumba |
| Profession | Ingénieur en énergie solaire |
| Domaine d'activité | Énergie renouvelable |
| Type d'énergie | Solaire |
| Poste | Ingénieur |
| Expérience | 12 ans |
| Structure | "Soleil Vert" |
| Zone d'opération | Nationale |
| Accès électricité | Oui |
| Source principale à domicile | Panneaux solaires |
| Consommation mensuelle | 200 kWh |
| Projets | Installation de 500 panneaux à l'Université |
| Cause détaillée | Coupures fréquentes du réseau national, coût élevé du groupe électrogène |
| Est malade ? | Non |

---

### Exemple 4 : Secteur Démographie

| Champ | Valeur |
|-------|--------|
| Secteur | Démographie |
| Nom | Katumbi |
| Prénom | Jeanne |
| Âge | 28 ans |
| Sexe | Féminin |
| Classification | Adulte (26-59 ans) |
| État civil | Divorcée |
| Commune | Annexe |
| Quartier | Kasapa |
| Profession | Commerçante |
| Taille ménage | 4 personnes |
| Nombre d'enfants | 2 |
| Nationalité | Congolaise |
| Lieu naissance | Lubumbashi |
| Année arrivée | 2020 |
| Motif migration | Travail |
| Cause détaillée | Migrations massives vers Lubumbashi à cause des opportunités économiques |
| Est malade ? | Non |

---

### Exemple 5 : Enfant (Mineur - Secteur Éducation)

| Champ | Valeur |
|-------|--------|
| Secteur | Éducation |
| Nom | Tshibola |
| Prénom | Kévin |
| Âge | 12 ans |
| Sexe | Masculin |
| Classification | Mineur (0-17 ans) |
| État civil | Célibataire |
| Commune | Lubumbashi |
| Quartier | Gambela |
| Profession | Élève |
| Niveau d'étude | Primaire |
| Établissement | Public |
| Classe | 6e année |
| Discipline | Général |
| Résultats | 65% (moyen) |
| Bourses | Non |
| Matériel | Non |
| Cause détaillée | Manque de manuels scolaires, classe de 60 élèves pour un seul enseignant |
| Est malade ? | Non |
## 5. ANNEXE : DÉCOUPAGE ADMINISTRATIF DE LUBUMBASHI

| Commune | Quartiers |
|---------|-----------|
| **Lubumbashi** (Centre-ville) | Gambela, Gambela II, Kalubwe, Kiwele, Lido-Golf, Lumumba, Malela, Météo, Kabulameshi, Makutano, Mampala (Cité GCM), Baudoin, Makomeno, La Légende |
| **Kampemba** | Bel-Air I, Bel-Air II, Kigoma, Kampemba, Kafubu, Bongonga, Naviund (Navyundu), Quartier Industriel |
| **Kamalondo** | Njanja, Kafubu, Kitumaini |
| **Kenya** | Lualaba, Luapula (Luapul), Luvua |
| **Katuba** | Musumba, Kisale, Kaponda (Nord et Sud), Bukama, Upemba, Lufira, Mwana-Shaba, N'sele, Kinyama, Kimilolo |
| **Ruashi** | Matoleo, Bendera, Luano (Luano 1 & 2), Kalukuluku, Shindaika |
| **Annexe** (urbano-rurale) | Kasapa, Kabeluka (Kalebuka), Kasungami (Kasangiri), Kimbembe, Kisanga, Luwowoshi, Munua, Navyundu (Naviundu), Kamasaka, Kamisepe, Kamatete, Kapanta |
