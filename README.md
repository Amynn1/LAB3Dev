# LAB3Dev
LAB 3 – Formulaire et navigation entre activités

# 📱 Android Intent Transfer : Lab Practice

Ce projet Java/Android met en avant l'interaction entre deux écrans (Activities) via le transfert de données utilisateur. L'application valide la saisie d'un formulaire et affiche un récapitulatif complet.

---

## 🌟 Points Forts du Projet
| Fonctionnalité | Description |
| :--- | :--- |
| **Saisie Intuitive** | Utilisation de champs texte optimisés pour le nom, l'email et le téléphone. |
| **Sélection de Ville** | Intégration d'un widget `Spinner` pour une sélection rapide. |
| **Navigation** | Passage d'arguments complexes via l'objet `Intent`. |
| **Interface** | Design structuré avec une barre de retour (Navigation) et un bouton d'envoi. |

---



## 💻 Développement & Logique
L'application repose sur les piliers suivants du développement Android :
* **Layouts XML** : Définition des champs de saisie (`EditText`) et des conteneurs.
* **Events** : Gestionnaire de clic (`OnClickListener`) sur le bouton d'envoi.
* **Data Flow** : 
    1. Récupération des données dans `MainActivity`.
    2. Envoi via `intent.putExtra()`.
    3. Extraction et affichage dans `Screen2`.

---

## 🔧 Installation Rapide
1. Téléchargez le code source.
2. Ouvrez le projet dans votre IDE (**Android Studio**).
3. Connectez un appareil ou lancez un émulateur.
4. Appuyez sur **Run** pour déployer l'application.





