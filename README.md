# Atelier Strand – Frisör Mall

Premium frisörhemsida byggd med **100% statisk Vite** – redo för Vercel.

---

## 🚀 Deploy till Vercel (3 steg)

### 1. GitHub
```bash
git init
git add .
git commit -m "initial commit"
git branch -M main
git remote add origin https://github.com/DITT-NAMN/frisor-mall.git
git push -u origin main
```

### 2. Vercel
1. Gå till [vercel.com](https://vercel.com) → "Add New Project"
2. Importera ditt GitHub-repo
3. **Framework Preset:** Vite (väljs automatiskt)
4. **Build Command:** `npm run build`
5. **Output Directory:** `dist`
6. Klicka **Deploy** ✅

**Inga extra inställningar behövs.**

---

## ✏️ Anpassa till ny kund

Sök och ersätt i `index.html`:

| Placeholder | Ersätt med |
|-------------|-----------|
| `Atelier Strand` | Salongens namn |
| `Göteborg` | Salongens stad |
| `Avenyn 42, 411 36 Göteborg` | Riktig adress |
| `031-000 000` | Riktigt telefonnummer |
| `info@atelierstrand.se` | Riktig e-post |
| `@atelierstrand` | Instagram-handle |
| Prisnumren | Salongens priser |
| Google Maps-sektionen | Riktig iframe-embed |

---

## 📦 Teknisk stack

- **Vite** (static build)
- Vanilla HTML/CSS/JS – noll beroenden
- `npm run build` → skapar `/dist/index.html`
- Ingen SSR, ingen server, ingen backend

---

## 💰 Affärsmodell

Sälj hemsidan för **3 000–8 000 kr/st** + **500–1 000 kr/mån** hosting/support.
Anpassning per kund tar ~30–60 min.
