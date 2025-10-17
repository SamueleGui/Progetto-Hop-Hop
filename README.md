# 🐰 Hop & Hop

**Hop & Hop** è un platform game 2D sviluppato con **Unity**, ispirato ai grandi classici come *Super Mario*.  
Il giocatore controlla un coniglio che deve superare ostacoli, raccogliere carote e sconfiggere nemici in livelli sempre più impegnativi.  

---

## 🎮 Panoramica

- **Genere:** Platform 2D  
- **Motore di gioco:** Unity 2021.3+  
- **Linguaggio:** C#  
- **Autori:** [Alyssa Chiodo Grandi](mailto:alyssa.chiodograndi@galileo.galileicrema.it) e [Samuele Gui](mailto:samuele.gui@galileo.galileicrema.it)  
- **Anno:** 2024  

---

## 🧩 Caratteristiche principali

- Movimento e salto del personaggio con input da tastiera  
- Interazioni con oggetti, nemici e collezionabili  
- Gestione delle collisioni (OnCollisionEnter2D / OnTriggerEnter2D)  
- Sistema di vite e punteggio basato sulle carote raccolte  
- Musiche di sottofondo e effetti sonori gestiti con `AudioManager.cs`  
- Grafica 2D realizzata con **Pixelorama**  
- Livelli con difficoltà crescente  

---

## 🗂️ Struttura del progetto

Assets/
├── Scripts/ # Script C# (PlayerController, Enemy, LevelManager, ecc.)
├── Art/ # Sprite, texture e animazioni
├── Audio/ # Musiche ed effetti sonori
├── Prefabs/ # Oggetti prefabbricati
├── Scenes/ # Menu, livello principale e fine gioco
└── ArtWork/ # Immagini e risorse grafiche aggiuntive

---

## 🖥️ Requisiti di sistema

- **Sviluppo:** Windows 10/11 o macOS 10.15+, Unity 2021.3+, Visual Studio 2019/2022  
- **Gioco:** Windows 7+ o macOS 10.13+  

---

## 🚀 Come eseguire il progetto

1. Clona la repository:
   ```bash
   git clone https://github.com/<tuo-username>/hop-and-hop.git
