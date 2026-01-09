# 🚀 IT SERVICES WEBSITE GENERATOR

---

## 🤖 AI INSTRUCTIONS

### WHEN YOU SEE USER INPUT (Domain):

**EXECUTE IMMEDIATELY:**

1. **Generate Brand Name** (if not provided):
   - Extract: `cloudvault.com` → "CloudVault"
   - Capitalize: `techsolutions.io` → "TechSolutions"
   - Multi-word: `abc-systems.com` → "ABC Systems"

2. **Use `write` tool** - NO conversation

3. **Create MULTIPLE files** to avoid timeout:
   - `generated-websites/{domain}/1-Brand-and-Sitemap.md` (300-400 lines)
   - `generated-websites/{domain}/2-Navigation-and-Pages.md` (500-700 lines)
   - `generated-websites/{domain}/3-SEO-Strategy.md` (300-400 lines)
   - `generated-websites/{domain}/4-Design-and-Implementation.md` (400-500 lines)

4. **Generate each file separately** - prevents timeout

5. **Follow examples** in `generated-websites/` folder

---

## 🚨 CONTENT RULES

### ✅ DO:
- Execute immediately on valid input
- Generate complete docs in single operation
- Include "END OF DOCUMENTATION" marker
- Use unique content (zero repetition)
- Professional corporate copy only
- Role-based descriptions ("Our cloud architects")
- Generic examples ("Enterprise clients")
- Evergreen content only
- Use email format: info@{domain}

### ❌ DON'T:
- Respond conversationally
- Ask questions (unless domain missing)
- Generate in chat (causes timeout)
- Use placeholder text
- Include staff names (except testimonials)
- Include specific pricing
- Include dates/years (except foundation)
- Include tech versions
- Include real company names

---

## 📋 QUALITY CHECKLIST

### Human Names:
- ❌ NO staff names → ✅ "Our leadership team"
- ❌ NO blog authors → ✅ "By [Company] Team"
- ❌ NO case study names → ✅ "CTO, Fortune 500"
- ✅ Testimonials ONLY with full context

### Pricing & Numbers:
- ❌ "$99/month" → ✅ "Contact for pricing"
- ❌ "500+ clients" → ✅ "Serving enterprises globally"
- ❌ "50 employees" → ✅ "Experienced team"

### Dates & Versions:
- ❌ "In 2024" → ✅ "Recently"
- ❌ "React 18.2" → ✅ "Modern React"
- ✅ "Established 2020" (foundation year OK)

### Copyright:
- ✅ "© 2020-present [Company]"
- ❌ "© 2020-2025"

---

## 📖 DOCUMENT STRUCTURE (SPLIT INTO 4 FILES)

### File 1: `1-Brand-and-Sitemap.md` (300-400 lines)
```markdown
# [BRAND] - BRAND FOUNDATION & SITEMAP

## 1. BRAND FOUNDATION
- Brand positioning statement
- 3 tagline options
- Value propositions
- Target audience

## 2. COMPLETE SITEMAP
- All 25-45 pages organized by category
- URL structure
- Page hierarchy

---
END OF FILE 1
```

### File 2: `2-Navigation-and-Pages.md` (500-700 lines)
```markdown
# [BRAND] - NAVIGATION & PAGE CONTENT

## 3. NAVIGATION STRUCTURE
- Header navigation
- Footer navigation
- Mobile menu

## 4. PAGE CONTENT
- Hero sections for all pages
- Main content sections
- CTAs for each page

---
END OF FILE 2
```

### File 3: `3-SEO-Strategy.md` (300-400 lines)
```markdown
# [BRAND] - SEO STRATEGY

## 5. SEO STRATEGY
- Page titles (all pages)
- Meta descriptions (all pages)
- Focus keywords
- Schema markup
- Content optimization

---
END OF FILE 3
```

### File 4: `4-Design-and-Implementation.md` (400-500 lines)
```markdown
# [BRAND] - DESIGN SYSTEM & IMPLEMENTATION

## 6. DESIGN SYSTEM
- Color palette
- Typography
- UI components
- Spacing system

## 7. IMPLEMENTATION PLAN
- Development timeline
- Milestones
- Launch checklist
- Maintenance plan

---
END OF FILE 4
```

---

## 🔧 GENERATION APPROACH

- **MULTI-FILE** (default): 4 separate files to avoid timeout
- **SEQUENTIAL**: Generate files one by one (File 1 → File 2 → File 3 → File 4)
- **ORGANIZED**: Each file covers specific sections for easy navigation

---

## 🔍 SERVICE AUTO-DETECTION

| Domain Contains | Auto-Suggest |
|----------------|--------------|
| "cloud" | Cloud Computing, DevOps |
| "cyber", "security" | Cybersecurity, Compliance |
| "data", "analytics" | Data & Analytics, BI |
| "ai", "ml" | AI/ML, NLP |
| "dev", "software" | Software Development |
| "blockchain" | Blockchain, Web3 |
| "iot" | IoT Platform |
| "tech", "solutions" | Multi-service |

---

## 📅 AUTO-GENERATION RULES

### Brand Name:
- `cloudvault.com` → "CloudVault"
- `techsolutions.io` → "TechSolutions"
- `abc-systems.com` → "ABC Systems"

**Rules:** Remove TLD, capitalize words, replace hyphens with spaces

### Contact Email:
- `cloudvault.com` → "info@cloudvault.com"
- `techsolutions.io` → "info@techsolutions.io"
- `abc-systems.com` → "info@abc-systems.com"

**Rule:** Always use `info@{domain}` format

### Establishment Year:
- Domain Registration Date: 2015
- Calculate: 2015 - 1 = **"Established 2014"**

### Target Country:
- **US** (default): American English, Fortune 500
- **UK**: British English, FTSE 100, colour
- **Australia**: Australian English, ASX
- **Canada/India/Singapore**: Regional variants

---

## ✅ SUCCESS CHECK

After generation:
- ✅ 4 files created in `generated-websites/{domain}/` folder
- ✅ File 1: Brand & Sitemap (300-400 lines)
- ✅ File 2: Navigation & Pages (500-700 lines)
- ✅ File 3: SEO Strategy (300-400 lines)
- ✅ File 4: Design & Implementation (400-500 lines)
- ✅ Each file has "END OF FILE" marker
- ✅ NO placeholders
- ✅ NO staff names
- ✅ NO pricing
- ✅ NO dates (except foundation)

---

**IF YOU'RE AN AI: ACT NOW. CREATE 4 FILES SEQUENTIALLY USING WRITE TOOL.**

---

## 👤 INPUT TEMPLATE

```
═══════════════════════════════════════
     IT SERVICES WEBSITE REQUEST
═══════════════════════════════════════

Domain: [yourcompany.com] (REQUIRED)

───────────────────────────────────────
OPTIONAL (auto-generated if blank):
───────────────────────────────────────

Brand Name: 
Services: 
Domain Registration Date: 
Target Audience Country: 
Generation Mode: 

═══════════════════════════════════════
```

**SIMPLEST:**
```
Domain: yourcompany.com
```

---

## 💡 EXAMPLES

### 1. Ultra-Minimal
```
Domain: cloudvault.com
```
→ Brand="CloudVault", Services=Auto, Target=US

### 2. With Country
```
Domain: techsolutions.co.uk
Target Audience Country: UK
```
→ UK English, FTSE 100 refs

### 3. With Est. Year
```
Domain: cloudglobal.com
Domain Registration Date: 2015
```
→ "Established 2014"

### 4. Full Custom
```
Domain: dronelogistics.io
Brand Name: DroneLogistics Pro
Services: Drone Fleet, Aerial Delivery
Target Audience Country: Australia
```

Domain: twikiweb.com
Domain Registration Date: 01-Nov-2000
Target Audience Country: India

---

## 📖 EXAMPLE SITES

Check `generated-websites/` for:
- JustWebAds (32 pages)
- KTSDigital (42 pages)
- TwikiNet (32 pages)
- SoftwareByMatrix (38 pages)

---

## 📋 PASTE INPUT HERE

**AI creates file immediately when you paste:**

---

Domain: twikiweb.com
Domain Registration Date: 01-Nov-2000
Target Audience Country: India

---



