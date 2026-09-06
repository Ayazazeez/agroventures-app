# 🌿 Agroventures Premier App & Analytics Suite - GitHub Pages Operating Guide

Welcome to your official **Agroventures Premier Data Application & Analytics Suite**. 

This application is 100% standalone, serverless, and optimized for **free hosting on GitHub Pages**. It contains an institutional investor presentation deck, interactive ROI simulator, audited corporate archive, and a **Commercial Plantation Data & Analytics Dashboard**.

---

## 1. Project Folder Layout

```text
Agroventures APP/
├── .nojekyll                    # Tells GitHub Pages to serve static files directly
├── .gitignore                   # Excludes temporary and system files
├── index.html                   # High-performance SaaS Data Application entry point
├── Agroventures_Instructions.md # This deployment & operating guide
└── Assets/
    ├── Logo.png.jpg             # High-resolution corporate logo
    ├── Agreements and Documents/
    │   ├── AVGH Company Details.pdf
    │   ├── cultivation_agreement.pdf
    │   ├── Investment.Plan2026.pdf
    │   └── legal_docs.pdf
    ├── Certifications/
    │   ├── AgroVentures_BestWorkplaces_Manufacturing_Rank04_2026.png
    │   ├── AgroVentures_Company_Profile_Vanilla_Export_Brochure.jpg
    │   ├── AgroVentures_GreatPlaceToWork_CEO_Statement_2025.webp
    │   ├── AgroVentures_GreatPlaceToWork_Certificate_2025.jpg
    │   ├── AgroVentures_HeadOffice_And_Branch_Network_Directory.PNG
    │   ├── AgroVentures_ISO_22000_2018_FoodSafety_Certificate.jpg
    │   ├── AgroVentures_Logo.jpg
    │   ├── AgroVentures_Milestones_Excellence_Award_2025.jpg
    │   └── AgroVentures_Plantation_Estates_Gallery_Map.jpg
    ├── Company Vision/
    │   ├── Director of HR_s Message.png
    │   ├── Group Chairman_s Message (Mr. Nilanga Karunarathne).png
    │   └── Mr. Nilanga Karunarathne - Chairman of Agroventures.mp4 (Web FastStart)
    └── My Details/
        ├── Ayaz Azeez - Potrait.jpg
        └── Business Card.JPG
```

---

## 2. Deploying to GitHub Pages in 3 Simple Steps

### Step 1: Create a Repository on GitHub
1. Go to [github.com/new](https://github.com/new) and log in.
2. Enter a repository name (e.g. `agroventures-premier` or `agroventures-app`).
3. Set the repository to **Public** (required for free GitHub Pages).
4. Do NOT initialize with a README, .gitignore, or license (we already created them for you).
5. Click **Create repository**.

### Step 2: Push Your Code from Your Desktop
Open PowerShell or Terminal inside this folder (`c:\Users\ayazk\Desktop\Agroventures APP`), and run:

```bash
git add .
git commit -m "Deploy Agroventures Premier Data App to GitHub Pages"
git remote add origin https://github.com/<YOUR-GITHUB-USERNAME>/<YOUR-REPO-NAME>.git
git push -u origin main
```

*(Replace `<YOUR-GITHUB-USERNAME>` and `<YOUR-REPO-NAME>` with your GitHub username and repository name).*

### Step 3: Enable GitHub Pages
1. In your GitHub repository, click **Settings** (top tab).
2. On the left sidebar, click **Pages**.
3. Under **Build and deployment** > **Branch**:
   - Select branch: `main`.
   - Folder: `/ (root)`.
   - Click **Save**.
4. In about 30–60 seconds, GitHub will generate your live permanent URL:
   ```text
   https://<YOUR-GITHUB-USERNAME>.github.io/<YOUR-REPO-NAME>/
   ```
5. You can now share this URL directly with prospective investors, partners, and clients worldwide!

---

## 3. Running Locally Without Internet / Server

Because the application is built using modern standalone web standards:
- Simply **double-click `index.html`** in this folder.
- It will open immediately in any browser (Chrome, Edge, Safari, Firefox) on Windows, Mac, or tablet with full styling, charts, videos, and PDFs functional!

---

## 4. Key Application Features

### 📊 1. Commercial Plantations Data Analytics Suite
- **Macro KPI Cards**: Tracked vines (`4,000,000+`, `↑ +24.0% YoY`), national export target (`$1.00B by 2030`), scale (`24 Commercial Estates`), and investor base (`12,440+ Title Holders`).
- **5-Year Harvest Yield Curve**: Visualizes green pods vs. gourmet cured Bourbon vanilla (strict 6:1 conversion ratio), demonstrating **130 KG cured vanilla** grossing **Rs. 19.5M** per 10P unit.
- **Contractual Return Comparison Matrix**: Compares 10P, 20P, 40P, 90P, 230P, and 940P tiers with monthly cash flows and Year 5 buyback covenants (**3.75x return multiple**).
- **Estates Master Directory**: Search and filter all 24 estates across districts (Matale, Kandy, North Western, Western, Sabaragamuwa), with a split investigation panel showing soil pH, elevation, irrigation specs, and deed status, plus a 1-click button to book estate visits via WhatsApp.

### 🌓 2. SaaS Design System & Theming
- Instant **Dark / Light mode** toggle (☀️ / 🌙) in the top header.
- Typography: `DM Sans` for clean reading, `JetBrains Mono` for financial telemetry.

### ✨ 3. AI Data Analyst ("Chat with your Data")
- Works 100% on GitHub Pages without requiring any backend server!
- Built-in analytical intelligence calculates returns, explains the Matale deed structure, and suggests follow-up questions.
- Optional: If you wish to connect directly to Google's live Gemini Flash model, you can enter your Gemini API key in the chat settings, which is safely stored only inside your browser's `localStorage`.

### 📜 4. Media, Documents & Executive Contact
- **Chairman Nilanga Karunarathne's Visionary Address**: FastStart web-optimized streaming video.
- **Official PDF Downloads**: Legal deeds, cultivation agreements, investment plans, and company background details.
- **Audited Accreditations**: All 9 official certificates and badges.
- **Executive Advisor Card**: Integrated high-resolution Business Card modal viewer & download for Ayaz Azeez.
