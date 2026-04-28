# TradeForge Academy
### 30 Kunlik XAUUSD Savdo Ta'lim Platformasi

---

## Fayl tuzilishi
```
tradeforge/
├── index.html
├── netlify.toml
├── netlify/
│   └── functions/
│       └── ai.js
└── README.md
```

---

## Netlify ga joylashtirish

### 1. GitHub ga yuklang
1. github.com → "New repository" → nom: `tradeforge`
2. "uploading an existing file" → barcha fayllarni yuklang
3. "Commit changes"

### 2. Netlify ga ulang
1. netlify.com → GitHub bilan kiring
2. "Add new site" → "Import an existing project"
3. GitHub → `tradeforge` ni tanlang
4. "Deploy site"

### 3. API kalitni kiriting ⭐
1. Netlify → "Site configuration" → "Environment variables"
2. "Add a variable":
   - Key: `GEMINI_API_KEY`
   - Value: sizning `AIzaSy...` kalitingiz
3. "Save"
4. "Deploys" → "Trigger deploy" → "Deploy site"

### Tayyor!
Netlify sizga bepul link beradi: https://sizning-nom.netlify.app
