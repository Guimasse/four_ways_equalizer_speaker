# Enceinte Audio 4 Voies avec Égaliseur  
**Conception d'une enceinte audio haut de gamme intégrant un égaliseur pour une personnalisation avancée du son.**  

## Introduction  
Ce projet a pour objectif de concevoir une enceinte audio 4 voies (Tweeter, Medium, Woofer, Subwoofer) qui rivalise avec les produits haut de gamme du marché. L'enceinte sera équipée d'un système d'égalisation, ou égaliseur, permettant d'ajuster précisément le niveau de filtrage de chaque voie pour une expérience sonore optimale.  

---

## Caractéristiques de l'enceinte  

### Entrées audio  
L'enceinte devra être compatible avec plusieurs types d'entrées audio pour s'adapter aux différents appareils modernes :  
- **Jack 3.5 mm**  
- **Jack 6.35 mm** *(optionnel)*  
- **USB Type-C** *(optionnel)* : De nombreux appareils, comme les smartphones, ne possèdent plus de prise jack. Une version avec entrée USB Type-C serait donc pertinente à envisager.  
- **Bluetooth**  

#### Gestion des entrées  
Un système de basculement automatique entre les sources devra être implémenté. Dans la première version, seules une entrée jack et une entrée Bluetooth seront intégrées. Par exemple, la connexion d'une prise jack devra automatiquement désactiver l'entrée Bluetooth.  

---

### Alimentation  
L'alimentation joue un rôle central dans la conception, car elle influence directement le choix de l'amplification.  

- **Autonomie sur batterie** : L'enceinte devra être capable de fonctionner sur batterie avec une autonomie moyenne de 2 heures.  
- **Type d'amplification** : Les amplificateurs de classe D, reconnus pour leur haut rendement (supérieur à 90 %), seront privilégiés pour permettre une utilisation sur batterie. Les amplificateurs de classe A, B ou AB sont exclus en raison de leurs faibles rendements énergétiques.  

#### Système de protection  
L'enceinte devra être utilisable aussi bien sur secteur que sur batterie. Des mécanismes de protection seront nécessaires pour prévenir les dommages aux composants, notamment à la batterie.  

---

### Système de contrôle  
Le système de contrôle sera assuré par un microcontrôleur et offrira une interface utilisateur intuitive :  
- **Interface utilisateur (IHM)** :  
  - Un écran LCD pour l'affichage des paramètres.  
  - Des boutons pour naviguer et configurer les réglages.  
- **Contrôle numérique des éléments** :  
  - Contrôle du volume via des amplificateurs opérationnels (AOP) à gain réglable numériquement.  
  - Contrôle du module Bluetooth par le microcontrôleur.  
- **Prototype et intégration finale** :  
  - Le développement initial se fera avec un Arduino Uno pour sa facilité de prototypage.  
  - Une carte dédiée sera conçue pour la version finale, afin d'assurer une intégration propre et professionnelle.  

---

### Contrôle et protection des haut-parleurs  
Pour éviter les problèmes de saturation et de surintensité pouvant endommager les haut-parleurs :  
- Un système de contrôle actif devra être mis en place pour surveiller les niveaux de puissance.  
- Des mécanismes de protection seront intégrés pour limiter les risques.  

---

### Fonctionnalités supplémentaires (optionel)
L'enceinte pourra également offrir des fonctionnalités avancées pour augmenter sa polyvalence :

Extensions audio : Possibilité de connecter des haut-parleurs externes, tels que des haut-parleurs de voiture, tout en gardant le subwoofer actif sur l'enceinte centrale. Cela permettra d'élargir le champ sonore et d’adapter l’installation à différents environnements.
Réactions lumineuses : Intégration d'un système permettant de connecter des appareils lumineux (LEDs, bandes lumineuses, etc.) qui réagissent en synchronisation avec la musique. Cette fonctionnalité ajoutera une dimension visuelle et immersive à l'expérience audio, idéale pour des fêtes ou des ambiances personnalisées.

---

Ce cahier des charges définit les spécifications clés pour développer une enceinte audio performante, polyvalente et adaptée aux standards actuels du marché. Le projet mettra l'accent sur la qualité sonore, l'autonomie, et une expérience utilisateur fluide.