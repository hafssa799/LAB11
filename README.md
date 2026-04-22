# LAB 11 : Bypass Root Detection avec Frida

 1. Objectif du Lab

Ce laboratoire a pour objectif de :

Comprendre comment les applications Android détectent le root
Utiliser Frida pour contourner cette détection
Implémenter des hooks Java et natifs

##  Vérification de l’environnement


<img width="364" height="70" alt="image" src="https://github.com/user-attachments/assets/88fec9a1-ea22-4685-acf0-7356571011fd" />

<img width="163" height="48" alt="image" src="https://github.com/user-attachments/assets/eaabb4ab-ddfd-4f44-825a-70fded428e3b" />

##  Vérifier l’architecture

<img width="279" height="38" alt="image" src="https://github.com/user-attachments/assets/91e50b20-7fac-4892-b15f-a5c9c59f3d97" />


##  Télécharger Frida

- https://github.com/frida/frida/releases

## Push vers Android

Dans le bon dossier :

<img width="625" height="47" alt="image" src="https://github.com/user-attachments/assets/6a34a4f0-8040-4712-91c1-c8d9ce27b65a" />

## Donner les permissions

<img width="593" height="23" alt="image" src="https://github.com/user-attachments/assets/2851ca47-0fb2-4f6b-bb18-dc122c5462c6" />

## Lancer frida-server

<img width="386" height="58" alt="image" src="https://github.com/user-attachments/assets/700fd15e-743f-45ec-8237-69aba6f5693b" />

<img width="376" height="313" alt="image" src="https://github.com/user-attachments/assets/6e803b5c-d793-4ecb-ae79-d0ee467d9d03" />

# Étape 1 — Démarrage et repérage du package

<img width="421" height="23" alt="image" src="https://github.com/user-attachments/assets/78a7cc88-c83d-4b34-8673-030514ae2f46" />

## Étape 2 — Script Frida (bypass Java) prêt à l’emploi

<img width="890" height="476" alt="image" src="https://github.com/user-attachments/assets/17396997-8507-4ebd-9b09-94fcd7fd961d" />
