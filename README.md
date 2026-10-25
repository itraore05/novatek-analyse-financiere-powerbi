# 💼 NOVATEK — Analyse des performances financières et de la santé économique

![Power BI](https://img.shields.io/badge/Power%20BI-F2C811?style=flat&logo=powerbi&logoColor=black)
![DAX](https://img.shields.io/badge/DAX-ratios%20financiers-informational?style=flat)
![Power Query](https://img.shields.io/badge/Power%20Query-ETL-blue?style=flat)
![Finance](https://img.shields.io/badge/Analyse-financière-6A1B9A?style=flat)

> Tableau de bord Power BI de **3 pages** pour évaluer la santé financière de l'entreprise NOVATEK sur 6 exercices (2018-2023) : bilan, compte de résultat et portefeuille clients.
> Projet d'analyse financière — mars 2025.

---

## 🎯 Objectifs

- Évaluer la **structure financière** : actifs, dettes, capitaux propres, solvabilité
- Mesurer la **rentabilité** : chiffre d'affaires, marges, résultat net
- Analyser le **portefeuille clients** : répartition géographique, segments, délais de paiement
- Offrir une lecture interactive par exercice, segment et pays

## 🧭 Structure du tableau de bord

### 1. Bilan financier
- Actif total, dettes totales, ratios d'**endettement** et de **solvabilité**
- Évolution de l'actif, des dettes et des capitaux propres (2018-2023)
- Actif courant vs non courant, dettes à long terme vs dettes courantes
- Autonomie financière et liquidité

### 2. Compte de résultat
- Chiffre d'affaires, **taux de croissance**, marge brute, marge d'exploitation, résultat net
- Évolution du CA par exercice et structure des revenus et charges
- Comparaison CA / résultat d'exploitation / résultat net

### 3. Portefeuille clients
- Nombre de clients, montant des achats, **délai moyen de paiement**
- Répartition par pays et par segment (B2B, B2C, Gouvernement)
- Top 10 des clients et évolution du délai de paiement

## 📈 Chiffres clés

| Indicateur | Valeur |
|---|---|
| Actif total | **117 M** |
| Dettes totales | **76 M** |
| Chiffre d'affaires | **112 M** |
| Taux de croissance du CA | **25,5 %** |
| Marge brute | **56 M** |
| Résultat net | **31 M** (marge nette ≈ 27 %) |
| Clients | **200** — achats totaux **11 M** |
| Délai moyen de paiement | **32,9 jours** |

**Insights :**
- 📈 Une croissance du CA de 25,5 % avec une **marge nette d'environ 27 %** : l'activité est rentable.
- ⚖️ Le niveau d'endettement (76 M de dettes pour 117 M d'actifs) est à surveiller, avec un poids important des dettes à long terme.
- ⏱️ Le délai moyen de paiement remonte en fin de période (≈ 39 jours en 2023) : un point d'attention pour la trésorerie.
- 🌍 Le portefeuille est bien réparti entre pays européens et nord-américains, avec une majorité de clients B2B.

## 🖼️ Aperçu

*(captures du dashboard — ajoutées après import des fichiers)*

## 📁 Contenu du dépôt

| Élément | Description |
|---|---|
| `dashboard/` | Tableau de bord Power BI (`.pbix`) et export PDF |
| `documentation/` | Documentation du projet et code DAX |
| `data/` | Jeux de données CSV utilisés par le tableau de bord |

## ▶️ Utilisation

Ouvrir le fichier `.pbix` dans `dashboard/` avec **Power BI Desktop**, puis filtrer par exercice, segment ou pays.

## 👤 Auteur

**Ismaël Traoré** — Développeur Data & IA
📧 contact.traoreimael@gmail.com · 💼 [LinkedIn](https://www.linkedin.com/in/ismael-traor%C3%A9-m-4007a2225/)
