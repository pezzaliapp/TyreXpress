# TyreXpress — PWA Marketplace per Gomme Usate

PWA minimale per gommisti e clienti finali. MVP con inserimento locale (localStorage) e lista annunci.
Pronta per essere estesa con backend (Firebase/REST) e geolocalizzazione.

## Avvio
Apri `index.html` in un server statico (o GitHub Pages). La PWA registra il Service Worker e funziona offline di base.

## Struttura
- index.html — UI + JS inline
- manifest.json — PWA manifest
- service-worker.js — cache asset principali
- icons/ — icone PWA (192, 512, favicon)
