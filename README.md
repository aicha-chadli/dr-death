# 🔍 Projet Power BI : Dr Death – Analyse des meurtres de Harold Shipman

## 📌 Contexte

Harold Shipman, surnommé "Dr Death", est considéré comme l’un des tueurs en série les plus prolifiques de l’histoire britannique. Médecin généraliste de 1975 à 1998, il est responsable d’au moins **215 décès** de ses patients, principalement des personnes âgées. Ce projet vise à **analyser les victimes et leurs profils** pour comprendre les tendances dans ses crimes.

---

## 🎯 Objectif

> Répondre à la question :  
> **Quels types de personnes Harold Shipman a-t-il assassinées, et quand sont-elles mortes ?**

Grâce à **Power BI**, l’objectif est de créer un **dashboard interactif** qui met en évidence :
- Les années les plus meurtrières
- Le profil des victimes (âge, sexe…)
- Les horaires des décès
- Des anomalies par rapport à d’autres médecins

---

## 🛠️ Outil utilisé – Microsoft Power BI

### ✔️ Présentation de Power BI
Power BI est un logiciel d’analyse de données développé par Microsoft permettant de créer :
- des **rapports visuels dynamiques** (dashboards)
- des **visualisations interactives**
- des **connecteurs multiples** (CSV, Excel, SQL, etc.)

### ✔️ Avantages :
- Interface intuitive
- Outils puissants (Power Query, DAX)
- Filtres interactifs et visuels dynamiques

### ✔️ Limites :
- Courbe d’apprentissage pour les débutants
- Certaines fonctionnalités avancées sont disponibles uniquement dans Power BI Pro

---

## 📁 Données utilisées

1. **`shipman-confirmed-victims.csv`**
   - Informations sur les victimes : nom, âge, date de décès
2. **`shipman-times-comparison.csv`**
   - Comparaison des heures de décès : Shipman vs autres médecins

---

## 📊 Visualisations créées

### 1. **Histogramme : Nombre de victimes par année**
- Montre la répartition annuelle des décès
- Permet d’identifier les années les plus meurtrières

### 2. **Graphique par tranche d’âge**
- Catégorisation des victimes par classes d’âge (0–40, 41–60, etc.)
- Montre que Shipman visait majoritairement les personnes âgées

### 3. **Courbe horaire de décès (comparaison)**
- Compare les heures de décès entre Shipman et d’autres médecins
- Met en lumière des **pics anormaux** en milieu de journée

### *(Facultatifs selon les données disponibles)*
- 📍 Carte des lieux de décès
- 🥧 Camembert par genre (hommes vs femmes)

---

## 🖼️ Aperçu du dashboard

*(Insère ici 2 à 4 captures d’écran de ton tableau de bord Power BI)*  
> Exemple : Histogramme annuel, courbe horaire, graphique par tranche d’âge

---

## 📌 Conclusion

L’analyse met en lumière :
- Une concentration importante de décès **entre 1993 et 1998**
- Une **prédominance de victimes âgées**
- Des **horaires de décès répétitifs** et suspects chez Shipman
- Des éléments que **les outils d’analyse auraient pu alerter plus tôt**

Ce projet montre comment **Power BI** peut être un **véritable outil de détection de patterns** dans des contextes critiques comme la médecine.

---

## 📚 Références

- [New Scientist - Could statistics have spotted the killer?](https://www.newscientist.com/article/dn7958-statistics-could-have-spotted-mass-murderer/)
- [Documentation officielle Power BI](https://learn.microsoft.com/fr-fr/power-bi/)
- [Tutoriel débutant Power BI – YouTube](https://www.youtube.com/watch?v=TmhQCQr_DCA)
- [Chaîne YouTube – Alexandre Stevens](https://www.youtube.com/@alexpbix)

---

## 👩‍💻 Auteur

Aicha Chadli  
Étudiante en analyse de données et visualisation  
Projet réalisé dans le cadre d’un apprentissage sur Power BI
