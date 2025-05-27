# 📘 Portail de ressources scientifiques — Projet Drupal

Projet démonstratif réalisé pour montrer la maîtrise de Drupal dans un contexte de gestion de ressources scientifiques en lien avec les enjeux sociétaux de l’intelligence artificielle.

---

## 🎯 Objectif

Créer un mini portail Drupal de type "Obvia", permettant :
- l’ajout et la classification de ressources scientifiques,
- l’organisation par taxonomie thématique,
- l’affichage structuré avec filtres.

---

## 🧠 Compétences démontrées

- Création de types de contenu personnalisés
- Utilisation de taxonomies
- Configuration de vues avec filtres exposés
- Gestion des fichiers et champs complexes
- Affichage personnalisable (tableaux, fiches, HTML)

---

## 📐 Structure du projet

### 📄 Types de contenu

- `Ressource scientifique` : titre, auteur, résumé, fichier PDF, mots-clés
- `Chercheur` (optionnel) : nom, bio, photo, ressources liées

### 🏷 Taxonomie

- Vocabulaire : `Thèmes`
- Termes : IA, Éthique, Environnement, Données ouvertes, Inclusion numérique

---

## 🔧 Étapes de mise en œuvre

### ✅ Étape 1 : Création du type de contenu `Ressource scientifique`
📸 *Insérer une capture d’écran du formulaire de création*

### ✅ Étape 2 : Création de la taxonomie `Thèmes`
📸 *Insérer une capture de la liste de termes*

### ✅ Étape 3 : Ajout du champ `Mots-clés`
📸 *Capture de la configuration du champ (Référence à un terme)*

### ✅ Étape 4 : Création de la vue `Catalogue de ressources`
- Filtres : thème, auteur
- Format : tableau ou liste HTML
📸 *Capture de la page publique avec filtres activés*

### ✅ Étape 5 : Ajout de ressources de test

| Titre | Auteur |
|-------|--------|
| L’IA et la justice sociale | Martin Dubois |
| Données ouvertes et gouvernance numérique | Alice Martin |
| Santé environnementale et technologies prédictives | Jean Dupont |
| Vers une IA éthique pour les villes intelligentes | Nadia Larivière |
| Inclusion numérique en contexte autochtone | Samuel Drouin |

📸 *Capture du back-office : `/admin/content`*

### ✅ Étape 6 : Mise en forme personnalisée
- Utilisation du style « Liste HTML »
- Réécriture du champ `Fichier` avec lien "Télécharger PDF"
📸 *Capture du rendu final*

---

## 📂 Dossier du projet

- `config/sync/` : export de la configuration Drupal *(facultatif)*
- `files/` : exemples de PDF téléversés
- `themes/obvia_theme/` : thème personnalisé *(si utilisé)*

---

## 📷 Captures recommandées

1. Formulaire `Ressource scientifique`
2. Taxonomie `Thèmes`
3. Champ `Mots-clés` configuré
4. Vue filtrable : catalogue
5. Page publique avec rendu final
6. Back-office `/admin/content`

---

## 🧾 Auteur

**Alain Kiemde**  
Projet réalisé en mai 2025 dans le cadre d’une démonstration de compétence pour un poste à l’Obvia.

---

> Ce projet met en valeur la capacité à structurer, organiser et présenter efficacement de la recherche scientifique via Drupal.
