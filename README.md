# Soundie

Un'app ambient sound rilassante basata su browser con 20+ suoni naturali e urbani. Perfetto per concentrazione, meditazione, studio o semplicemente per rilassarsi.

## ✨ Caratteristiche

- **20+ suoni ambientali**: Pioggia (leggera, forte, tuono, auto, ombrello), onde, fuoco, bosco, fiume, subacqueo, cavallo, rana, neve, treno, metro, bar, tastiera, macchina da scrivere, vinile, carta, lavanderia
- **Controllo volume master**: Regolazione globale con slider verticale
- **Timer programmabile**: 15 min, 30 min, 1 ora, 2 ore - stop automatico
- **Fullscreen**: Modalità immersiva per concentrazione totale
- **Pulsante muto**: Toggle veloce con memoria volume
- **GIF animate**: Ogni suono ha un'icona animata associata
- **Starfield dinamico**: Cielo stellato generato proceduralmente
- **Design elegante**: Dark theme moderno con accenti cyan
- **Tema responsive**: Adatto a desktop e mobile

## 🚀 Come usare

### Avvio
1. Apri `index.html` per il loading screen (5 secondi)
2. Oppure accedi direttamente a `soundie.html`

### Operazioni
- **Riproduci suono**: Clicca su qualsiasi cerchio per avviare/fermare
- **Regola volume**: Clicca l'icona altoparlante e usa lo slider
- **Muto**: Clicca l'icona altoparlante per toggle muto
- **Timer**: Clicca l'orologio, seleziona durata, premi "Imposta Timer"
- **Fullscreen**: Clicca l'icona fullscreen (Esc per uscire)

## 🎵 Suoni disponibili

**Pioggia**: Leggera, Forte, Tuono, Auto, Ombrello  
**Natura**: Onde, Fuoco, Bosco, Fiume, Subacqueo, Cavallo, Rana, Neve  
**Urbani**: Treno, Metro, Bar, Tastiera, Macchina da Scrivere, Vinile, Carta, Lavanderia

## 🎨 Design

- **Dark theme**: Gradiente blu-viola profondo (#0f0c29 → #24183f)
- **Accent color**: Cyan (#6dd5ed)
- **Font**: Pacifico per titolo, Segoe UI per UI
- **Animazioni**: Rotazione ring per playing, twinkle stars, glow pulse

## 🔊 Tecnica audio

- Audio HTML5 con loop infinito
- Volume master indipendente per ogni suono
- Controllo tramite proprietà `.volume`
- State management via classe `SoundPlayer`

## ⚙️ Funzionalità avanzate

**Timer intelligente**: 
- Seleziona durata e premi "Imposta"
- Display in tempo reale (mm:ss)
- Stop automatico di tutti i suoni allo scadere
- Stato attivo mostrato in status bar

**Muto con memoria**:
- Mantiene volume precedente
- Icona aggiornata dinamicamente
- Sincronizzazione slider

**Fullscreen API**:
- Richiesta completa fullscreen
- Fallback per Safari (webkit)
- Uscita pulita con Esc

## 📱 Responsive

- Desktop: Griglia 5 colonne
- Tablet/Mobile: Griglia 2 colonne
- Controlli adattivi (45px → 40px)

## 🔒 Privacy

Nessun dato inviato. Audio riprodotto localmente dal browser.

---

Rilassati con Soundie. 🎵