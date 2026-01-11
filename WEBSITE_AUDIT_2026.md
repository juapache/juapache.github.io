# 🔍 COMPREHENSIVE WEBSITE AUDIT
## juapache.github.io | Research-Portfolio | Data-Analysis-Portfolio | Class-Portfolio
**Audit Date:** January 11, 2026  
**Last Website Update:** January 7, 2026 (Prisoner's Dilemma implementation)  
**Audit Scope:** Website architecture, portfolio alignment, broken links, content gaps, and integration opportunities

---

## 📊 EXECUTIVE SUMMARY

### Overall Status: **FUNCTIONAL BUT FRAGMENTED**
- ✅ **Website:** Polished, navigable, with 3 complete interactive tools
- ⚠️ **Portfolio Alignment:** Significant disconnect between website promises and repository content
- 🔴 **Content Gaps:** Multiple "Coming Soon" placeholders and broken link chains
- 💡 **Opportunity:** Class-Portfolio is underutilized; could strengthen teaching presence

### By the Numbers
| Metric | Count | Status |
|--------|-------|--------|
| Complete interactive tools | 3 | ✅ Trust Paradox, Polarization Spiral, Prisoner's Dilemma |
| Research pillars (promised) | 5 | 1 complete, 1 partial, 3 coming soon |
| Data viz projects (website) | 5 | 2 complete, 3 planned/empty |
| Dead/missing PDF links | 9 | 8 teaching files + 1 sample brief |
| Blog posts (published) | 0 | 2 placeholders only |
| Teaching resources (visible) | 1 | Prisoner's Dilemma game |
| Portfolio sections not on website | 2 | Conflict Data Analysis, Policy Research Tools |

---

## 🔴 CRITICAL ISSUES (Fix Immediately)

### 1. **Dead PDF Links on Teaching Page**
**Severity:** HIGH  
**Location:** [teaching.html](teaching.html), [teaching-es.html](teaching-es.html)  
**Details:**
- References in website but files don't exist in `/pdfs/`:
  - ❌ `eu-digital-law.pptx`
  - ❌ `peace-innovation.pptx`
  - ❌ `peace-innovation-resources.pdf`
  - ❌ `sample-brief.pdf` (referenced in manifest.json)

**Current State:** Links are hardcoded but PDFs missing
```json
// manifest.json references non-existent file:
{
  "title": "Sample Policy Brief",
  "file": "sample-brief.pdf",  // ❌ MISSING
  "description": "Policy brief on AI governance and ethical considerations."
}
```

**Impact:** Teaching.html appears broken; resource links fail  
**Solutions:**
- Option A: Upload teaching materials to `/pdfs/`
- Option B: Remove teaching download links and direct to Class-Portfolio instead
- Option C: Create placeholder PDFs with "Coming Soon" notices

---

### 2. **Empty Blog Posts**
**Severity:** MEDIUM  
**Location:** [blog.html](blog.html), [index.html](index.html) blog cards  
**Details:**
- **Post 1 ("Hello Law!"):** Exists but contains only poetry + placeholder code (no real content)
- **Post 2:** Placeholder title with "[Date]" — essentially non-functional
- Both marked "Coming Soon" on blog index

**File Status:**
- ✅ Files exist: `blog-posts/01-blog-post-title-here.html`, `blog-posts/02-another-blog-post-title.html`
- ❌ Content: Minimal/placeholder only

**Impact:** Blog section feels incomplete; reduces credibility  
**Solutions:**
- Write real blog post content OR hide until ready
- Update titles to be descriptive
- Consider linking to Medium/Substack if blog is low priority

---

### 3. **Broken Resources Section**
**Severity:** MEDIUM  
**Location:** [index.html](index.html) `#resources` section  
**Details:**
- JavaScript loads resources from `pdfs/manifest.json`
- Manifest only references `sample-brief.pdf` which doesn't exist
- Section displays error message: "Coming soon — Upload PDFs to /pdfs/ and add entries"
- No actual downloadable resources available

**Impact:** Users can't access promised policy briefs/resources  
**Solutions:**
- Add real resources to `/pdfs/` and update manifest.json
- OR temporarily remove resources section and re-enable when ready

---

## ⚠️ PORTFOLIO ↔ WEBSITE MISALIGNMENT

### Issue A: **Research Portfolio Structure vs. Website Claims**

#### Pillar 01: Technodiversity & Decolonization
```
📂 Status: Coming Soon (correct)
├── ✅ Has: README.md (exists, minimal)
├── ✅ Has: research-questions.md
├── ✅ Has: notes/ folder (but mostly empty)
└── ✅ Has: First working paper (Spanish)
```
**Website Claim:** "Epistemic sovereignty and material impacts of AI supply chains"  
**Actual Content:** Skeleton structure; minimal narrative  
**Alignment:** 🟡 STATUS ACCURATE but could use brief intro README

---

#### Pillar 02: Algorithmic Governance
```
📂 Status: ✅ UPDATED (promoted from "Coming Soon")
├── ✅ README.md (comprehensive)
├── ✅ research-questions.md (detailed)
├── ✅ notes/ (populated: literature-review.md, research-notes.md)
├── ✅ working-papers/
│   ├── spanish/perfilado-algoritmico-manipulacion-conductual.md
│   └── english/ (translations)
├── ✅ bibliography.md (annotated)
└── ✅ case-studies/ (1 case study: CNIL vs Google 2022)
```
**Website Claim:** "Working papers on behavioral profiling, dark patterns, and GDPR/EU AI Act compliance"  
**Actual Content:** ✅ MATCHES — Comprehensive working papers, bibliography, first case study  
**Alignment:** ✅ EXCELLENT | Website status correctly updated Jan 7, 2026

---

#### Pillar 03: Peace Innovation & Technology
```
📂 Status: Coming Soon (correct)
├── ✅ README.md (exists, minimal)
├── ✅ research-questions.md (minimal)
└── ❌ notes/ (empty)
```
**Website Claim:** "Conflict-sensitive design loops and curriculum work for peace tech"  
**Actual Content:** Skeleton only  
**Alignment:** 🟡 STATUS ACCURATE but no differentiation from Pillar 01

---

#### Pillar 04: Global South Perspectives
```
📂 Status: Coming Soon (correct)
├── ✅ README.md (exists, minimal)
└── ❌ notes/ (empty)
```
**Website Claim:** "Non-aligned data governance and South-South coalitions for AI policy"  
**Actual Content:** Skeleton only  
**Alignment:** 🟡 STATUS ACCURATE but structure doesn't reflect content promise

---

#### Pillar 05: AI Strategy NLP
```
📂 Status: ~90% Complete (✅ WORKS)
├── ✅ README.md (comprehensive, well-documented)
├── ✅ notebooks/ (01_data_extraction.ipynb, 02_nlp_analysis.ipynb, 03_visualization.ipynb)
├── ✅ src/ (text_processing.py, visualization.py)
├── ✅ data/ (raw/, processed/, external/ structure)
├── ✅ results/ (figures/ directory)
└── ✅ requirements.txt (dependencies documented)
```
**Website Claim:** "Comparing how national AI strategies frame Safety/Ethics vs Development/Access using TF-IDF and spaCy pipelines"  
**Actual Content:** ✅ MATCHES — Project properly structured and documented  
**Alignment:** ✅ EXCELLENT | Model for other projects; hero card on index page justified

---

### Issue B: **Data-Analysis-Portfolio Projects vs. Website**

#### **NOT MENTIONED ON WEBSITE but exists in repo:**

**01. Conflict Data Analysis**
```
📂 Location: Data-Analysis-Portfolio/01-conflict-data-analysis/
├── data/ (empty)
├── notebooks/ (empty)
├── results/ (empty)
└── src/ (empty)
```
- **Website Visibility:** ❌ ZERO
- **Content Status:** Structure only
- **Opportunity:** Could be featured in Data Lab if content added

---

**02. Policy Research Tools**
```
📂 Location: Data-Analysis-Portfolio/02-policy-research-tools/
├── {notebooks/
│   └── examples/ (exists but empty)
└── docs/ (empty)
```
- **Website Visibility:** ⚠️ MENTIONED (card says "Coming Soon") but link goes to empty GitHub directory
- **Content Status:** Empty
- **Issue:** Implies more complete than reality; no example notebooks

---

**03. Data Visualization Sub-Projects**
```
📂 Location: Data-Analysis-Portfolio/03-data-visualization/
├── algorithmic-impact-dashboard/ (empty)
├── polarization-spiral/ (empty)
├── policy-landscape-maps/ (empty)
└── trust-paradox/ (empty)
```
- **Website Visibility:** ⚠️ Cards exist on data-lab.html; 2 complete (Trust Paradox, Polarization Spiral), 2 "Coming Soon"
- **Content Status:** 
  - ✅ Trust Paradox: Complete interactive tool + documentation
  - ✅ Polarization Spiral: Complete interactive tool + documentation
  - ❌ Algorithmic Impact Dashboard: 0% (folder only)
  - ❌ AI Strategy Explorer: Website-only placeholder (no repo folder)
  - ❌ Policy Landscape Maps: 0% (empty)

---

### Issue C: **Class-Portfolio Invisible on Website**

**Status:** Completely absent from website  
**Actual Content:**
```
📂 Class-Portfolio/01-intro-peace-conflict-studies/
├── README.md ✅
├── lessons/
│   └── 01-foundational-concepts/
│       └── lesson.md ✅
├── assignments/ ✅
└── resources/ ✅
```

**Why This Matters:**
- 📚 Teaching section exists on website but only links to PDF downloads (broken)
- 📂 Class-Portfolio has actual lesson content but isn't linked
- 🔗 Missing opportunity to drive traffic to teaching materials
- 👨‍🎓 Strengthens credibility: shows you DO have course content

**Gap:** Teaching page should link to `lesson_intropc.html` (exists on website) AND consider linking to Class-Portfolio repository

---

## 🟡 CONTENT GAPS & INCONSISTENCIES

### 1. **Pillar Status Clarity**
**Problem:** Website says "Coming Soon" for Pillars 01, 03, 04 but doesn't differentiate their readiness
- Pillar 01 has more structure than Pillar 04 (2 files vs. 1)
- No indication whether "Coming Soon" = weeks away or months away
- Users can't gauge project momentum

**Recommendation:** Add clarity markers
```html
<!-- Instead of generic "Coming Soon": -->
<span class="tag small">Research Notes Coming Soon (Q1 2026)</span>
<!-- Or: -->
<span class="tag small">Foundational Framework in Development</span>
```

---

### 2. **Broken Navigation Chains**
**Examples:**
- Teaching page → references Research-Portfolio notes → notes folders exist but are mostly empty
- Data Lab → "Policy Research Tools" link → GitHub repo → empty directory
- Blog page → blog cards → minimal placeholder content

**Pattern:** Website promises exceed repository depth

---

### 3. **Missing Project READMEs**
**Empty directories without README.md:**
- ❌ `Research-Portfolio/01-technodiversity-and-decolonization/` (only has research-questions.md)
- ❌ `Research-Portfolio/03-peace-innovation-and-technology/` (no content README)
- ❌ `Research-Portfolio/04-global-south-perspectives/` (no content README)
- ❌ `Data-Analysis-Portfolio/01-conflict-data-analysis/` (no README)
- ❌ `Data-Analysis-Portfolio/02-policy-research-tools/` (no README)

**Impact:** Visitors don't know what these projects contain or why they're useful

---

## 🟢 WHAT'S WORKING WELL

### 1. ✅ **Complete Interactive Tools (3 Total)**
- **Trust Paradox** (trust-paradox.html + trust-paradox-es.html)
  - Fully functional slider interactions
  - Methodology documented
  - Academic references included
  
- **Polarization Spiral** (polarization-spiral.html + polarization-spiral-es.html)
  - Complex visualization of feedback loops
  - Educational framing
  - Clean, intuitive UI
  
- **Prisoner's Dilemma Escalation Game** (4 files: basic + parte2, EN + ES)
  - NEW as of Jan 7, 2026
  - Proper game theory mechanics (payoff matrices, probabilistic behavior)
  - Educational content explaining security dilemma
  - Cross-linked navigation between parts

**Value Proposition:** These tools effectively demonstrate technical capability and pedagogical approach

---

### 2. ✅ **Pillar 02 (Algorithmic Governance) Complete**
- Well-structured README
- Comprehensive literature review
- Working papers in Spanish and English
- First case study (CNIL vs Google 2022)
- Annotated bibliography
- Website correctly labeled "Updated"

**This pillar is the model for what 01, 03, 04 should become**

---

### 3. ✅ **AI Strategy NLP Project (Pillar 05)**
- Complete project structure
- Notebooks, code, requirements documented
- Featured prominently on website
- Links corrected (pointing to correct repository)
- Matches website promise exactly

**This project demonstrates reproducibility and professional standards**

---

### 4. ✅ **Website Infrastructure**
- Clean, responsive design
- Bilingual setup (EN/ES) with proper hreflang tags
- SEO metadata in place
- Schema.org structured data for search engines
- Consistent navigation
- Contact page fully functional
- About page with embedded CV
- Pixelfed profile now linked (just added)

---

### 5. ✅ **Repository Structure**
- Clear separation: Research-Portfolio (conceptual) vs Data-Analysis-Portfolio (technical)
- Consistent naming conventions
- LICENSE files in place (CC BY-NC 4.0)
- .gitignore properly configured
- Git history maintained

---

## 🔵 STRATEGIC RECOMMENDATIONS

### Phase 1: IMMEDIATE (This Week)
**Goal:** Fix broken links and remove placeholder confusion

1. **Teaching Page:**
   - ✅ Prisoner's Dilemma already linked (NEW)
   - [ ] Remove PDF download links OR upload files
   - [ ] Consider: Link to Class-Portfolio instead of PDFs
   - [ ] Action: Choose one path and implement

2. **Blog:**
   - [ ] Publish first real blog post OR remove from index
   - [ ] Remove "Coming Soon" post 02 OR write content
   - [ ] Update manifest with actual blog structure

3. **Resources Section:**
   - [ ] Add 1-3 actual policy briefs to `/pdfs/`
   - [ ] Update `manifest.json`
   - [ ] Test JavaScript resource loader
   - [ ] OR hide section until ready

---

### Phase 2: SHORT-TERM (1-2 Weeks)
**Goal:** Deepen portfolio credibility

1. **Expand Pillar 02:**
   - [ ] Add 2-3 more case studies (fintech, employment sectors)
   - [ ] Would take ~3-5 hours per case study
   - [ ] Makes pillar more comprehensive

2. **Add Project READMEs:**
   - [ ] Create README for Pillar 01 (explain why minimal + timeline)
   - [ ] Create README for Pillars 03, 04 (even if minimal)
   - [ ] Create README for Data Analysis projects
   - [ ] Each ~1 hour; 5 hours total

3. **Policy Research Tools:**
   - [ ] Add 2-3 example notebooks to `/02-policy-research-tools/{notebooks/examples}/`
   - [ ] Create README explaining what these tools do
   - [ ] Links on website then become meaningful

---

### Phase 3: MEDIUM-TERM (2-4 Weeks)
**Goal:** Increase content depth

1. **Class-Portfolio Integration:**
   - [ ] Link teaching.html to Class-Portfolio GitHub
   - [ ] Consider: Create standalone lesson landing page
   - [ ] Strengthens teaching credentials
   - [ ] Opportunity: Use as model for other course offerings

2. **Pillar 01 Content:**
   - [ ] Write 2-3 research notes
   - [ ] Add timeline to website
   - [ ] Convert to "In Development" instead of "Coming Soon"

3. **Blog Strategy:**
   - [ ] Decide: Invest in blog or link to external platform?
   - [ ] If investing: Establish 2-week posting cadence
   - [ ] If external: Link to Medium/Substack from website

---

### Phase 4: ONGOING (Strategic)
**Goal:** Portfolio coherence and transparency

1. **Status Badges:**
   - Add project status indicators:
     ```html
     <span class="badge complete">✓ Complete</span>
     <span class="badge in-progress">⏳ In Development</span>
     <span class="badge planned">📋 Planned</span>
     ```

2. **Transparency Dates:**
   - Add "Last Updated" to project cards
   - Helps users understand project momentum

3. **Conflict Data Analysis Decision:**
   - [ ] Keep and develop (add to website)
   - [ ] Deprioritize (remove from portfolio)
   - [ ] Archive (keep but mark as inactive)

4. **Documentation Standards:**
   - Ensure every project has:
     - README explaining purpose + scope
     - Link to GitHub repository
     - Status indicator
     - Last updated date

---

## 📋 QUICK CHECKLIST FOR NEXT 7 DAYS

### Must-Do
- [ ] Fix or remove teaching PDF links
- [ ] Populate or hide resources section
- [ ] Handle blog post placeholders (publish or remove)

### Should-Do
- [ ] Add README to empty research pillars
- [ ] Add example notebooks to Policy Research Tools
- [ ] Link Class-Portfolio from teaching.html

### Nice-To-Do
- [ ] Add status badges to project cards
- [ ] Add "Last Updated" dates
- [ ] Expand Pillar 02 with 1-2 new case studies

---

## 🎯 PRIORITY MATRIX

| Task | Impact | Effort | Priority |
|------|--------|--------|----------|
| Fix teaching links | HIGH | LOW | 🔴 DO FIRST |
| Hide/populate resources | HIGH | LOW | 🔴 DO FIRST |
| Blog post decision | MEDIUM | MEDIUM | 🟡 THIS WEEK |
| Policy Research Tools examples | MEDIUM | MEDIUM | 🟡 THIS WEEK |
| Add project READMEs | MEDIUM | LOW | 🟡 THIS WEEK |
| Pillar 01-04 content | LOW | HIGH | 🟢 ONGOING |
| Class-Portfolio integration | MEDIUM | LOW | 🟢 NEXT WEEK |
| Status badges | LOW | MEDIUM | 🟢 POLISH |

---

## 📊 FINAL ASSESSMENT

### Strengths
✅ Website is well-designed and functional  
✅ Three complete, sophisticated interactive tools  
✅ Bilingual implementation properly executed  
✅ Research portfolio has strong conceptual foundation  
✅ Pillar 02 shows depth and rigor  
✅ AI Strategy NLP demonstrates technical capability

### Weaknesses
❌ Significant disconnect between promises and content  
❌ Multiple broken links undermine credibility  
❌ Placeholder content feels incomplete  
❌ Class-Portfolio invisible despite strong teaching materials  
❌ Data-Analysis-Portfolio underutilized on website

### Opportunities
💡 Expand Pillar 02 case studies (quick wins for credibility)  
💡 Add documentation to empty projects (signal progress)  
💡 Integrate Class-Portfolio (strengthen teaching section)  
💡 Create status badges (transparency builds trust)  
💡 Develop Policy Research Tools (makes links meaningful)

---

## 🚀 RECOMMENDED 90-DAY ROADMAP

**Month 1: Fix + Document**
- Fix broken links (1-2 days)
- Add READMEs to all projects (1 week)
- Integrate Class-Portfolio (1-2 days)
- Result: Website reflects actual content state

**Month 2: Deepen**
- Expand Pillar 02 (2-3 case studies, 1-2 weeks)
- Add Policy Research Tools examples (3-5 days)
- Develop Pillar 01 initial content (1 week)
- Result: Portfolio feels more substantial

**Month 3: Polish**
- Add status badges and dates (2-3 days)
- Coordinate blog or external platform (3-5 days)
- Review and consolidate (1 week)
- Result: Professional, transparent portfolio

---

## 📞 NEXT STEPS

1. **Decide:** Which broken links to fix? (teaching PDFs, resources, blog)
2. **Prioritize:** Which portfolio gaps matter most? (content depth, documentation, integration)
3. **Allocate:** Time for each phase (quick wins vs. strategic investments)
4. **Communicate:** Update to-do.md with decisions and timeline

---

**Audit prepared:** January 11, 2026  
**Portfolio version:** As of January 7, 2026 (Prisoner's Dilemma implementation)  
**Next recommended audit:** April 11, 2026 (post Phase 2-3)

