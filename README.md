# 📱 Aplicació de Subhastes en Directe (Live Auctions App)

## 📌 Descripció del projecte

Aquest projecte consisteix en el desenvolupament d’una **aplicació mòbil de subhastes en directe**, inspirada en un model híbrid entre plataformes de subhastes online i aplicacions de streaming en temps real (tipus eBay + Twitch).

L’aplicació permet als venedors **subhastar productes en viu**, mentre que els usuaris poden **pujar en temps real**, interactuar mitjançant un xat en directe i seguir l’evolució de la subhasta de manera immediata. El projecte posa el focus principal en **l’experiència live**, la rapidesa de les pujades i la sensació d’esdeveniment en temps real.

L’aplicació està desenvolupada amb **React**, seguint una arquitectura modular i escalable, amb una interfície moderna, clara i minimalista.

---

## 🎯 Objectiu del projecte

Crear una aplicació mòbil que:
- Centralitzi subhastes en temps real.
- Permeti la interacció directa entre compradors i venedors.
- Prioritzi la immediatesa i la competitivitat de les pujades.
- Diferenciï clarament entre subhastes amb càmera i sense càmera.

---

## 🔴 Tipus de subhasta en directe

L’aplicació admet **dos tipus de subhasta live**:

### 1. Subhasta Live amb càmera
- El venedor transmet el producte mitjançant **streaming de vídeo**.
- Els usuaris poden veure el producte en temps real.
- Inclou xat en directe, historial de pujades i comptador de temps.
- Indicador visual **“EN DIRECTE 🔴”**.

### 2. Subhasta Live sense càmera
- No hi ha transmissió de vídeo.
- Es mostra una **imatge o carrusel del producte**.
- Manté el sistema de pujades en temps real, xat i comptador.
- Pensada per a subhastes ràpides o productes ja coneguts.

Ambdós tipus comparteixen la mateixa lògica de subhasta, adaptant únicament el component visual superior.

---

## 🧭 Navegació general de l’aplicació

L’aplicació utilitza una **navegació moderna amb barra inferior (Bottom Tab Bar)**, formada per cinc seccions principals:

- **Home**
- **Buscar**
- **Directe**
- **Favorits**
- **Perfil**

El botó **Directe** és l’eix central de l’app i permet accedir ràpidament a les subhastes en curs.

---

## 🏠 Pantalles principals

### Home
- Subhastes en directe.
- Subhastes pròximes amb recordatoris.
- Subhastes destacades.
- Categories.
- Subhastadors populars.

### Buscar
- Barra de cerca.
- Filtres per:
  - Categoria.
  - Preu.
  - Temps restant.
  - Tipus de subhasta (amb càmera / sense càmera).
- Resultats dinàmics.

### Directe
- Feed de subhastes en viu.
- Prioritat a les subhastes actives.

### Favorits
- Subhastes guardades.
- Subhastadors seguits.
- Accés a notificacions.

### Perfil
- Gestió del perfil d’usuari.
- Historial de pujades.
- Compres realitzades.
- Mètodes de pagament i adreces.
- Suport i FAQ.

---

## 🎥 Pantalla de Subhasta en Directe (pantalla clau)

La pantalla de subhasta en directe és **el nucli principal de l’aplicació** i està dissenyada per facilitar una experiència ràpida i intuïtiva.

Inclou:
- Component superior adaptable:
  - Vídeo en streaming (si és amb càmera).
  - Imatge del producte (si és sense càmera).
- Preu actual destacat.
- Comptador de temps restant.
- Botó principal **“PUJAR +X€”** molt visible.
- Camp de puja manual.
- Historial de pujades en temps real.
- Xat en directe tipus streaming.
- Nombre d’usuaris connectats.
- Alertes com **“T’han superat la puja”**.

---

## 🏆 Estat final de la subhasta

- **Has guanyat la subhasta**  
  Resum del producte, preu final i accés al pagament.

- **Has perdut la subhasta**  
  Preu final i recomanacions de subhastes similars.

---

## 🛍️ Funcionalitats per a compradors

- Pujades en temps real.
- Xat en directe.
- Favorits i recordatoris.
- Historial de pujades.
- Gestió de compres i pagaments.
- Seguiment de subhastadors.

---

## 🧑‍💼 Funcionalitats per a venedors

- Perfil públic amb reputació i seguidors.
- Panell de control de subhastes:
  - Actives.
  - Pròximes.
  - Finalitzades.
- Creació de subhastes.
- Gestió de subhastes en directe.
- Moderació del xat.
- Visualització de pujades en temps real.

---

## ⭐ Funcionalitats opcionals

- Xat privat comprador–venedor.
- Valoracions després de la compra.
- Sistema de report d’usuaris i subhastes.

---

## 🎨 Disseny i experiència d’usuari

L’aplicació segueix un estil:
- Modern i minimalista.
- Basat en **cards**, comptadors grans i botons d’acció destacats.
- Centrat en el directe i la rapidesa a l’hora de pujar.
- Optimitzat per a dispositius mòbils.

---

## 🚀 Tecnologies

- **Frontend:** React
- **Arquitectura:** Components reutilitzables i gestió d’estat
- **Enfocament:** Temps real, experiència live i escalabilitat

*(Les tecnologies de backend i streaming es definiran en fases posteriors del projecte.)*

---

## 👥 Equip del projecte

- **Eduard Vilaseca**
- **Jordi Rocha**
- **Hugo Córdoba**
- **Roberto Lotrenau**

---

