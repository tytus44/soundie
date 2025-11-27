# Soundie 🌌

**Soundie** è un'applicazione web immersiva progettata per il relax, la concentrazione e lo studio. Offre una selezione curata di suoni ambientali che possono essere mixati tra loro per creare l'atmosfera perfetta, il tutto avvolto in un'interfaccia utente elegante con uno sfondo stellato animato.

## ✨ Caratteristiche Principali

* **🎧 Mixer Ambientale:** Riproduzione simultanea di più tracce audio (pioggia, tuoni, onde, fuoco, ecc.) con controllo del volume globale.
* **⏱️ Timer Intelligente:**
    * Timer integrato per sessioni di focus (15m, 30m, 1h, 2h).
    * Visualizzazione del countdown in tempo reale nella barra superiore.
    * Design moderno con pulsanti stile "Pillow" (a pillola).
    * Logica di stato (Imposta/Annulla) con feedback visivo.
* **📱 Design Responsivo:**
    * Layout a griglia adattivo: 4 colonne su schermi grandi, 2 su dispositivi mobili.
    * Ottimizzato per desktop, tablet e smartphone.
* **🎬 Intro Cinematografica:** Splash screen iniziale con animazioni CSS fluide che transiziona elegantemente verso l'applicazione principale.
* **🎨 UI/UX Moderna:**
    * Icone vettoriali minimaliste (libreria **Lucide**).
    * Effetti di "glassmorphism" (sfocature e trasparenze).
    * Feedback visivo al passaggio del mouse e al click (animazioni di rotazione, glow).
    * Sfondo animato con campo stellare generato proceduralmente.

## 🛠️ Tecnologie Utilizzate

* **HTML5:** Struttura semantica e accessibile.
* **CSS3:** Flexbox, CSS Grid, Keyframe Animations, Gradienti e Media Queries.
* **JavaScript (ES6+):** Programmazione a oggetti (classe `SoundPlayer`), gestione del DOM, logica del timer asincrona.
* **Librerie Esterne:**
    * [Lucide Icons](https://lucide.dev/) (per le icone vettoriali).
    * [Google Fonts](https://fonts.google.com/) (Font "Pacifico" per i titoli).

## 📂 Struttura del Progetto

Il progetto è strutturato come una **Single Page Application (SPA)** contenuta in un unico file HTML principale, che gestisce sia l'intro che l'app vera e propria.

```text
Soundie/
│
├── index.html          # Il file principale (HTML, CSS, JS unificati)
├── README.md           # Documentazione del progetto
└── sounds/             # Cartella contenente i file audio .mp3
    ├── piogga-leggera.mp3
    ├── pioggia-forte.mp3
    ├── ... (altri suoni)
    └── bar.mp3
