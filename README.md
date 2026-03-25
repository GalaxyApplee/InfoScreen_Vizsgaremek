InfoScreen - Iskolai Tájékoztató Rendszer
Az InfoScreen egy modern, webalapú keretrendszer, amely lehetővé teszi iskolai hirdetmények, események és üzenetek valós idejű kezelését és megjelenítését digitális kijelzőkön (TV-ken).

🚀 Funkciók
Központi Vezérlőpult: Adminisztrációs felület az üzenetek kezeléséhez.

Célzott üzenetküldés: Külön tartalom a diákok és a tanárok számára.

Digitális Kódfunkció: Kijelzők egyszerű párosítása generált kódok segítségével.

Élő Előnézet: Az üzenetek szerkesztés közben azonnal láthatóak "TV nézetben".

Sötét mód (Dark Mode): Modern, fekete-narancs (Neon-Glow) dizájn.

🛠️ Technológiai stack
Frontend: React.js, React Router, Bootstrap 5

Backend (ajánlott): Node.js / Express

Stílus: Custom CSS & Neon-Glow UI components

Ikonok: Bootstrap Icons

📦 Telepítés és használat
Előfeltételek
Node.js (v14+)

npm

Lépések
Klónozd a tárolót:

Bash
git clone https://github.com/felhasznalonev/infoscreen.git
Telepítsd a függőségeket:

Bash
cd infoscreen
npm install
Indítsd el a fejlesztői szervert:

Bash
npm start
Backend indítása (JSON Server esetén):

Bash
# Ha json-servert használsz teszteléshez
json-server --watch db.json --port 3000
🖥️ Képernyőképek
Tipp: Itt érdemes elhelyezni egy képet a Dashboard-ról vagy az Élő előnézetről.

📖 Használati útmutató
Bejelentkezés: Használd az adminisztrátori fiókodat a belépéshez.

Új üzenet: Válaszd az "Új üzenet" menüpontot, írd be a címet, a tartalmat, és válaszd ki a célközönséget.

Küldés: Kattints a "KÜLDÉS A KIJELZŐRE" gombra. A rendszer visszajelzést ad a sikeres mentésről.

Kijelzők kezelése: A Vezérlőpulton generálhatsz új párosítási kódokat a különböző TV-khez.

🤝 Hozzájárulás
Forkold a projektet.

Hozz létre egy Feature ágat (git checkout -b feature/NewFeature).

Commitold a változtatásokat (git commit -m 'Add some NewFeature').

Pushold az ágat (git push origin feature/NewFeature).

Nyiss egy Pull Request-et.

📜 Licenc
