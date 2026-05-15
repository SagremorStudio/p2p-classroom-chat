\# 🔧 P2P Osztálytermi Kommunikációs Rendszer



Ez a projekt egy \*\*valós Peer‑to‑Peer (P2P)\*\* kapcsolaton alapuló kommunikációs rendszer, amely akár \*\*19 számítógép\*\* (1 tanári + 18 diák) közötti valós idejű üzenet- és fájlmegosztást tesz lehetővé.



Nincs központi szerver – minden adat \*\*közvetlenül a gépek között\*\* áramlik a PeerJS segítségével.



\---



\## 💬 Chat és fájlmegosztás



\- Üzenet írása az input mezőbe → az \*\*első csatlakozott géphez\*\* kerül elküldésre  

\- Küldés: \*\*Enter\*\* vagy \*„Üzenet küldése”\* gomb  

\- \*\*Csoportos üzenet\*\*: minden csatlakozott gép megkapja  

\- Fájlok is minden csatlakozott géphez mennek  

\- Minden üzenetnél látható:

&#x20; - feladó

&#x20; - időbélyeg



\---



\## 📁 Fájlküldés



\- Képek, PDF-ek, dokumentumok küldése  

\- Képek előnézete közvetlenül az üzenetekben  

\- Egyéb fájlok letölthetők



\---



\## 📊 Vizuális visszajelzés



\- Csatlakozott gépek \*\*színváltással\*\* jelölve  

\- Valós idejű státusz megjelenítés  

\- Folyamatosan frissülő csatlakozási lista



\---



\## 💡 Többgépes tesztelés



\- Nyisd meg több böngészőablakban vagy külön eszközökön  

\- Oszd meg a Peer ID-ket a csatlakozáshoz  

\- Minden gép előre meghatározott ID-t kap  

&#x20; - pl. `classroom-teacher`, `classroom-student1`, `classroom-student2`, …



\---



\## 🔍 Automatikus gépfelismerés



\- Inicializáláskor a rendszer automatikusan megkeresi az \*\*online gépeket\*\*  

\- Csak az online gépek jelennek meg  

\- Csak az online gépekhez lehet csatlakozni



\---



\## 🖱️ Egyszerű csatlakozás



\- Kattints egy online gépre → automatikus csatlakozás  

\- Több géphez is csatlakozhatsz egyszerre  

\- A csatlakozott gépek listája valós időben frissül



\---



\## 📌 Funkciók összefoglalása



\- Valós P2P kommunikáció PeerJS-sel  

\- 19 gépes osztálytermi szimuláció  

\- Chat, csoportos üzenetek, fájlmegosztás  

\- Automatikus gépfelismerés  

\- Valós idejű státusz és vizuális visszajelzés  

\- Egyszerű, kattintásos csatlakozás



