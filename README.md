# 🌍 CPT PLANET

> *Where the PLANET comes together.*

**Grassroots community-based company from Cape Town, South Africa** pushing local music the old school way — selling MP3s, streetwear, and assisting artists with DSP distribution.

🔗 **Live**: https://searchplaybook-crypto.github.io/cptonline/index.html  
🎵 **YouTube**: [@CPTPLANET](https://www.youtube.com/@CPTPLANET)  
👥 **Human in the Loop**: [WeMustCreate](https://searchplaybook-crypto.github.io/SearchPlaybook/)

---

## 🚨 The Payment Friction Problem — Voice of Truth

### Why Payhip Doesn't Work for Cape Town Grassroots

We tried Payhip. It failed the community. Here's why:

#### ❌ **The Forex Trap**
- **Problem**: Payhip pays out in **USD** → ZAR conversion
- **Reality**: 
  - Artist sells R100 worth of music
  - Payhip converts at unfavorable rate (loses 5-8%)
  - 3-5 business day payout delay
  - Artist gets ~R92 after conversion fees
- **Impact**: **R8 lost per R100 sale** — that's food, data, studio time gone

#### ❌ **No Local Payment Methods**
- **What SA buyers want**: 
  - ✅ Instant EFT (Ozow, PayFast EFT)
  - ✅ SnapScan / Zapper
  - ✅ Capitec Pay / Bank App payments
  - ✅ Mobicred / RCS (buy now, pay later)
- **What Payhip offers**:
  - ❌ International credit cards only
  - ❌ PayPal (low adoption in SA townships)
- **Result**: **Trust collapse** — buyers see foreign checkout, abandon cart

#### ❌ **Digital Delivery Friction**
- Payhip sends download link via email
- SA email deliverability issues (Gmail spam filters, data costs)
- No WhatsApp delivery option (how most SA businesses operate)
- No SMS backup (critical for low-data users)

#### ❌ **The Trust Deficit**
- Cape Town township buyers **don't trust foreign checkouts**
- "Why am I paying in dollars for local music?"
- "Is this a scam? Why no SnapScan?"
- **Cultural mismatch**: Global platform vs. local reality

---

### ✅ **The Solution: SA-Native Payment Stack**

We're migrating to **Paystack** or **PayFast** because:

| Feature | Payhip (Old) | Paystack/PayFast (New) |
|---------|-------------|------------------------|
| **Currency** | USD (conversion loss) | **ZAR** (no forex) |
| **Payment Methods** | Card/PayPal only | **Card + EFT + SnapScan + Ozow + Capitec Pay** |
| **Payout Speed** | 3-5 days | **24-48 hours** |
| **Payout Currency** | USD | **ZAR direct to SA bank** |
| **Trust Factor** | Foreign checkout | **Local brand, local methods** |
| **Delivery** | Email only | **Email + WhatsApp + SMS** |
| **Fees** | 5% + forex | **2.9% + fixed** (no hidden costs) |

**Math**: R100 sale → Artist keeps R97.10 (vs R92 with Payhip)  
**That's R5.10 MORE per sale** — 5.5% increase in artist revenue.

---

## 🤖 WeMustCreate: Human in the Loop

**This is not an AI project. This is a human movement.**

### What WeMustCreate Does:

1. **Cultural Guardian**  
   - Ensures tech serves the community, not extracts from it
   - Vets every tool for local relevance (Does it work in Langa? In Khayelitsha?)
   - Protects artist interests over platform profits

2. **Technical Bridge**  
   - Builds zero-API, static-first infrastructure
   - No maintenance overhead for grassroots organizers
   - Privacy-first analytics (no surveillance capitalism)

3. **Trust Layer**  
   - WeMustCreate is the **accountable human** behind the code
   - Real person, real SA presence, real consequences
   - Not a faceless AI, not a Silicon Valley startup

4. **Iterative Co-Creation**  
   - Friday meetings with artists → Monday deployment
   - Feedback loops measured in days, not quarters
   - Technology adapts to culture, not vice versa

**The Voice of Truth**:  
> *"AI can build fast, but only humans can build right. WeMustCreate ensures every line of code serves the community that birthed it."*

---

## 🛠 Technical Stack

| Layer | Technology | Why |
|-------|-----------|-----|
| **Frontend** | HTML5 + Tailwind CSS (CDN) | Zero build, instant iteration, works on 3G |
| **SEO** | JSON-LD Schema + Open Graph | Google discovers artists, social shares convert |
| **Analytics** | Plausible (privacy-first) | GDPR compliant, no cookies, respects user privacy |
| **Hosting** | GitHub Pages | Free, fast, version-controlled, CDN global |
| **Payments** | Paystack/PayFast (migration in progress) | ZAR pricing, local methods, instant delivery |
| **Media** | YouTube (zero-API embed) | No backend, community-driven, works everywhere |
| **Accessibility** | WCAG 2.1 AA | Screen readers, keyboard nav, high contrast |

### ✅ Zero-API Architecture
- **No backend** = no server costs, no maintenance
- **No database** = no GDPR nightmares, no data breaches
- **Static HTML** = loads on 2G networks in townships
- **External checkout** = Paystack handles PCI compliance

---

## 📊 SEO & Schema Optimization

### Structured Data (JSON-LD)
- ✅ **Organization**: CPT Planet entity with SA location
- ✅ **MusicGroup**: Artist collective metadata
- ✅ **Product**: Each item with ZAR pricing, availability
- ✅ **WebSite**: Search action, canonical URLs
- ✅ **Geo Tags**: Cape Town coordinates for local SEO

### Meta Tags
- Open Graph (Facebook/WhatsApp previews)
- Twitter Cards (social sharing)
- Geo Tags (local search ranking)
- Multi-language support (en-ZA, af-ZA, xh-ZA)

### Performance
- Preconnect hints for fonts/CDN
- Lazy loading images (below fold)
- Eager loading hero image (LCP optimization)
- Font-display: swap (no FOIT)

---

## 📝 Friday Meeting Agenda Template

### ✅ Confirmed Decisions
- [x] Brand: Grassroots, Cape Town pride, "old school" distribution
- [x] Colors: CPT Red `#FF3333`, Yellow `#FFCC00`, Green `#00CC00`
- [x] Payment migration: Payhip → Paystack/PayFast
- [x] Currency: ZAR only (no USD confusion)

### 🔄 To Decide (Friday Session)
- [ ] **Payment Provider**: Paystack vs PayFast? (Demo both)
- [ ] **Delivery Method**: Email vs WhatsApp vs SMS?
- [ ] **Product Photography**: Use existing S3 assets or new shoot?
- [ ] **Artist Onboarding**: How do new artists join? (Form? WhatsApp?)
- [ ] **Domain**: cptplanet.co.za vs .com vs GitHub Pages subdomain?

### 🎯 Post-Meeting Actions
| Owner | Task | Deadline |
|-------|------|----------|
| WeMustCreate | Migrate to Paystack/PayFast | Monday EOD |
| Client | Provide 3 artist bios + track links | Friday EOD |
| WeMustCreate | Add WhatsApp delivery integration | Tuesday |
| Client | Confirm product photography needs | Friday meeting |

---

## 🚀 Deployment

### GitHub Pages (Current)
```bash
git remote add origin https://github.com/searchplaybook-crypto/cptplanet.git
git add .
git commit -m "feat: SEO + schema optimization + payment migration prep"
git push -u origin main
# Settings → Pages → Deploy from main branch
