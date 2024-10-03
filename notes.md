Filip Mruškovič 4.C 2.Skupina

Príkazy v Ubuntu termináli:
cd – change directory
ls – ukáže čo sa všetko nachádza 

Na inštaláciu NEXT.js si ako prvé si vložíme tento príkaz do terminálu: npx create-next-app@latest

Vytváranie nového projektu v NEXT.js:
What is your project named? my-app
Would you like to use TypeScript? No / Yes
Would you like to use ESLint? No / Yes
Would you like to use Tailwind CSS? No / Yes
Would you like your code inside a `src/` directory? No / Yes
Would you like to use App Router? (recommended) No / Yes
Would you like to use Turbopack for `next dev`?  No / Yes
Would you like to customize the import alias (`@/*` by default)? No / Yes
What import alias would you like configured? @/*

App je ako router 

Príkazy na vytvorenie stránky:
import Typography from "@mui/material/Typography";

export default function TermsConditions() {
return (
<Typography> Podmienky pouzivania tohto webu</Typography>
);
}

page.tsx
layout.tsx
not-found.tsx

príkazy github:
git init
it branch -m main
git config --global user.name "Filip9933"
it config --global user.email "filipmruskovi@gmail.com"
git remote add origin https://github.com/Filip9933/zoska-snap.git
git remote -v
git add.