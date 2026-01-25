# 🌊 Projet ROV-CPS3 Deep Explorer

Ce projet documente la fabrication d'un ROV (Remotely Operated Vehicle) haute performance, optimisé pour l'exploration jusqu'à 20 mètres de profondeur.
Ce projet étant prévu pour l'été 2026, nous préparons les plans 3d pour une visualisation et nous cherchons un sponsor (besoin d'environ 500-600€)

---

## 🛠 Détails de Conception Avancée

### 1. Système d'Étanchéité
Le coeur du sous-marin utilise un système de **double barrière** :
* **Tube principal :** PVC haute pression (PN16).
* **Fermeture :** Flasques en aluminium ou impression 3D (PETG) .
* **Passage de câbles :** remplissage des connecteurs à la résine époxy.



### 2. Propulsion et Vecteurs de Force
Configuration en **3 moteurs**  :
* **Moteurs A & B :** Propulsion horizontale et virages .
* **Moteur C :** Gestion de la profondeur (moteur vertical).

### 3. Électronique & Communication
Contrairement aux drones aériens, les ondes radio ne traversent pas l'eau. 
* **Lien Ombilical :** Utilisation d'un câble Ethernet.
* **Protocole :** Signal vidéo via un convertisseur Analogique -> USB ou via un pont Ethernet pour une caméra IP.
* Caméra FPV (basse luminosité de préférence)


**Premieres Ebauches sur solidworks**<img width="1366" height="768" alt="image" src="https://github.com/user-attachments/assets/5f1ea5d0-083e-4e82-a70d-5c1f70745363" />

---

## 📊 Spécifications Techniques

| Composant | Modèle Recommandé | Rôle |
| :--- | :--- | :--- |
| **Batterie** | LiPo 3S 5000mAh | Autonomie env. 45 min |
| **Moteurs** | Brushless  | Propulsion avec hélice 3 pales |
| **Capteur** | MS5837 | Capteur de pression (profondeur) |
| **IMU** | MPU6050 | Stabilisation  |

---

## ⚖️ Équilibrage et Flottabilité (Trim)

Le succès du CPS3 repose sur son **centre de gravité (CoG)** et son **centre de flottabilité (CoB)**.

1.  **Lestage :** Placer les batteries tout en bas du tube pour éviter que le ROV ne se retourne (effet quille).
2.  **Flottabilité Neutre :** Le ROV doit idéalement flotter très légèrement en surface. S'il s'arrête de moteur, il doit remonter lentement.
3.  **Ajustement :** Utiliser des blocs de mousse "noodle" sur le haut pour la flottabilité et du plomb au fond pour la stabilité.

---

