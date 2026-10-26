# 🐙 Octo-Hop Deluxe

![HTML5](https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black)
![Zero Dependencies](https://img.shields.io/badge/Dependencies-Zero-00FA9A?style=for-the-badge)

**Octo-Hop Deluxe** è un videogioco arcade sottomarino *mobile-first* ispirato a Flappy Bird, interamente sviluppato in **Vanilla JavaScript** e **HTML5 Canvas** all'interno di un singolo file (`index.html`), senza l'uso di librerie o asset esterni.

🎮 **[GIOCA ALLA DEMO LIVE SU GITHUB PAGES](https://davide23567.github.io/Octo-Hop/)**

---

## ✨ Caratteristiche Principali

* **🌊 Biomi Dinamici & Coralli Mobili:** Il fondale cambia atmosfera e palette cromatica man mano che il punteggio sale (Laguna Turchese, Zona Crepuscolare, Fossa Abissale, Corallo Lavico). Superati i 15 punti, gli ostacoli iniziano a muoversi verticalmente.
* **⚡ Power-Up & Valuta di Gioco:**
  * ⚪ **Perla Normale (+1):** Valuta base per gli acquisti nel negozio.
  * 🟡 **Perla Dorata (+5):** Rara e preziosa.
  * 🛡️ **Scudo Bolla:** Assorbe un impatto fatale contro i coralli o i bordi dello schermo.
  * 🧲 **Magnete:** Attira automaticamente tutte le perle nelle vicinanze per 8 secondi.
* **🔥 Sistema "Near Miss" (Passaggio al Pelo):** Sfiora i coralli senza toccarli per ottenere un bonus immediato di **+2 Perle** ed effetti visivi dedicati.
* **🛒 Negozio Skin Integrato:** Sblocca ed equipaggia 10 creature marine (dal Polpo 🐙 fino all'Orca 🐋 e al Pinguino 🐧).
* **🎵 Audio 8-Bit Procedurale:** Effetti sonori retro sintetizzati in tempo reale tramite **Web Audio API** (nessun file `.mp3` o `.wav` esterno).
* **🎨 Fisica "Juicy" & Parallasse:** Animazioni *Squash & Stretch* sul salto, scia idrodinamica, particelle, *screen shake*, raggi solari subacquei e fondale in parallasse.
* **🌍 Multilingua & Salvataggi Automatici:** Traduzione istantanea **Italiano / Inglese** e salvataggio automatico di Record, Perle, Skin e preferenze tramite `localStorage`.

---

## 🕹️ Come Giocare

* **Smartphone / Tablet:** Tocca qualsiasi punto dello schermo per nuotare verso l'alto.
* **PC / Desktop:** Clicca con il tasto sinistro del mouse per nuotare.

---

## 🚀 Installazione ed Esecuzione Locale

Il progetto è racchiuso in un'architettura **Single-File** per garantire massima portabilità e caricamento istantaneo:

1. Clona il repository:
   ```bash
   git clone [https://github.com/davide23567/Octo-Hop.git](https://github.com/davide23567/Octo-Hop.git)
   
