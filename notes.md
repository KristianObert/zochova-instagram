Kristián Obert 4.C

1. hodina(doplnenie)
nový súbor dev pomocou základných príkazov. + súbor zoska-instagram

-------------------------

instalacia a pluginy
What is your project named? zoska-snap
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes

-------------------------
npm run dev = dev kod
-------------------------
vyhradené názvy súborov
page.tsx
layout.tsx
not-found.tsx

http://localhost:3000

Vytvorili sme si rôzne podstránky. A vytvorili konštrukciu pre náš projekt.

git config --global user.name "zochova-instagram"
git config --global user-email "kristianobertweb@gmail.com"
git remote add origin https...

GitHub – aplikacia na pracu s projektami v kode + backup.

zacali sme pracovat na kostre instagramu
Kostra sa robi preto, lebo musime zacat od zakladu apky

Prihlasili sme sa do vercelu(potom do githubu vo verceli)


Zistili sme ze musime dat do prazdnych pagov v kostre kod.
-----------------------------------------------------
// src/app/podmienky/page.tsx


import Typography from "@mui/material/Typography";
import Container from "@mui/material/Container";

export const metadata = { title: "Podmienky | ZoškaSnap" };

export default function TermsConditions() {

  return (
    <Container>
      <Typography> Podmienky používania </Typography>
    </Container>
  );
}
----------------------------------------------------
4 veci sa menia, podmienky hore, title, function a typography


Nahodil som anglicku klavesnicu aby som mohol zakomentovat kod

npm install @mui/material @emotion/react @emotion/styled
npm install @mui/icons-material @mui/material @emotion/styled @emotion/react

npm run build na skontrolovanie

ked niesu errory, uploadujeme

------------------------------------------------------
Dnes sa nám trom zrušil wls a zacali sme robit vo windows command line
git clone https://github.com/KristianObert/zochova-instagram.git
git config user.name "KristianObert"
git config user.email "kristianobertweb@gmail.com"
git remote -v
npm install

Prihlasili sme sa do gitu a natiahli projekt

Dobiehal som hodiny co som chybal a prirabal folder prispevok a txs subor page
NavBar.tsx v componentoch som dobiehal od spoluziakov ale hadzalo mi to navbar dolava tak som pridal prikaz
<Box sx={{ width: '100%', position: 'fixed', bottom: 0, left: 0 }}>
a potom som to mal v strede.

Submit ako NavBar done + poznamky

npm run dev
npm run build
npm start 

---------------------------------
dalsia hodina
dodal som podstranku o mne a stiahol info iconu z mui
