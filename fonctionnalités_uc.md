# ⚙️ Fonctionnalités principales et cas d’utilisation – Chefchaouen Bleu Durable

---

## 👤 Personas concernés

- **Lina Benali**, 27 ans — jeune professionnelle à Casablanca, passionnée de voyages authentiques et de nature.  
- **Karim El Idrissi**, 32 ans — guide touristique à Chefchaouen, passionné par le tourisme durable et la promotion des initiatives locales.

---

## 🧩 Objectif

Permettre aux **visiteurs** et **contributeurs** de **découvrir, publier et partager** des informations sur le **tourisme durable à Chefchaouen** dans un **espace collaboratif en ligne**.

---

## 🧠 Liste des fonctionnalités (Méthode MoSCoW)

| Fonctionnalité | Description | Priorité | Justification |
|----------------|-------------|-----------|----------------|
| Créer un compte utilisateur | S’inscrire et gérer son profil | **Must** | Essentiel pour publier et interagir |
| Gérer ses articles | Ajouter ou gérer ses articles avec texte et photos | **Must** | Cœur du projet pour valoriser les initiatives locales |
| Consulter les articles | Lire les articles récents et populaires | **Must** | Permet aux visiteurs de découvrir les initiatives |
| Commenter / liker / sauvegarder un article | Interagir avec le contenu | **Should** | Encourage la participation et permet de garder ses articles favoris |
| Rechercher / filtrer des articles | Trouver rapidement un type d’activité (hébergement, artisanat, nature…) | **Should** | Améliore l’expérience utilisateur |
| Gérer utilisateurs et articles (admin) | Ajouter, modifier ou supprimer tout contenu inapproprié | **Must** | Maintenir la qualité et la sécurité du blog |
| Partager un article | Copier le lien ou partager sur les réseaux sociaux | **Could** | Favorise la diffusion en dehors de la plateforme |

---

## 💬 Cas d’utilisation (UC)

| ID | Acteur | Cas d’utilisation (UC) | Priorité |
|----|--------|-------------------------|-----------|
| UC1 | Utilisateur | S’inscrire et gérer son profil | **Must** |
| UC2 | Utilisateur | Publier, modifier ou supprimer ses articles | **Must** |
| UC3 | Visiteur | Consulter les articles récents et populaires | **Must** |
| UC4 | Utilisateur | Commenter, liker ou sauvegarder un article | **Should** |
| UC5 | Visiteur / Utilisateur | Rechercher ou filtrer les articles par type d’activité | **Should** |
| UC6 | Admin | Gérer tous les articles et utilisateurs | **Must** |
| UC7 | Utilisateur | Partager un article sur les réseaux sociaux | **Could** |

---

## 🧭 Mini diagramme de cas d’utilisation (version texte)

          +-------------------------------------------+
          |         Chefchaouen Bleu Durable          |
          +-------------------------------------------+
                 /                |                \
                /                 |                 \
     +----------------+   +----------------+   +--------------------+
     |  Voir Articles |   | Publier Article|   | Gérer Utilisateurs |
     |                |   |                |   |      et articles   |
     +----------------+   +----------------+   +--------------------+
            |                    |                       |
      [Visiteur]           [Utilisateur]              [Admin]
