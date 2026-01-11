# Website & Portfolio To-Do List
**Status Report: juapache.github.io + Research-Portfolio + Data-Analysis-Portfolio**  
**Last Audit:** January 11, 2026 (Comprehensive audit + website enhancements)  
**Last Updated:** January 11, 2026 (Contact links, blog labels, Pixelfed profile)

---
## ✅ UPDATES COMPLETED TODAY (January 11, 2026)

### Contact Design Redesign (Latest)
- ✅ Redesigned contact links in contact.html and contact-es.html
- ✅ Changed from inline text layout to separate card boxes
- ✅ Grid layout: `repeat(auto-fit, minmax(240px, 1fr))` - responsive 4-column grid
- ✅ Each card has: 24px padding, background panel color, 1px border, 12px border-radius
- ✅ Hover effect: shadow lift + translateY(-2px) for interactive feel
- ✅ Title as `<h3>` with bold styling
- ✅ Description text in muted color with proper line-height
- ✅ Much more permanent and noticeable design

### Pixelfed Added to Index Pages
- ✅ Added Pixelfed link to [index.html](index.html) contact section
- ✅ Added Pixelfed link to [index-es.html](index-es.html) contact section
- ✅ Maintained existing layout (no design changes to index pages)
- ✅ Pixelfed appears in all 4 locations: contact pages (cards) + index pages (links)

### Home Button Navigation
- ✅ Added "Home" to top navigation bar on all website pages
- ✅ English pages: "Home" → `index.html`
- ✅ Spanish pages: "Inicio" → `index-es.html`
- ✅ Applied to: about, research, teaching, contact, data-lab, blog, all interactive tools
- ✅ Also applied to: lesson_intropc, trust-paradox, polarization-spiral (both EN/ES)
- ✅ Also applied to: all blog post pages
- ✅ Note: Game pages (Prisoner's Dilemma) already had Home links built into their UI

### Contact Page Enhancements
- ✅ Added descriptive text to all contact options (Email, GitHub, LinkedIn, Pixelfed)
- ✅ English descriptions: nerdy peace talk, repos, professional profile, photo portfolio
- ✅ Spanish translations: conversaciones nerds, repositorios, perfil profesional, portafolio de fotos
- ✅ Applied to both [contact.html](contact.html) and [contact-es.html](contact-es.html)
- ✅ Styled with `.muted` color and proper spacing

### Blog Post Corrections
- ✅ "Hello Law!" blog post: Changed status from "Coming Soon" → "poetry" label
- ✅ Accurate reflection: Blog post already exists at `blog-posts/01-blog-post-title-here.html`
- ✅ Applied to [blog.html](blog.html)

### Social Profile Integration
- ✅ Pixelfed link added to contact pages (from Jan 11 earlier work)
- ✅ Pixelfed added to schema.org `sameAs` array in both index pages
- ✅ Profile: https://pixelfed.social/huan

### Website Audit Documentation
- ✅ Created comprehensive [WEBSITE_AUDIT_2026.md](WEBSITE_AUDIT_2026.md)
- ✅ Identified: 9 broken PDF links, 3 complete projects, critical gaps in portfolio alignment
- ✅ Provided: 90-day roadmap, priority matrix, quick wins checklist

---
## ✅ UPDATES COMPLETED PREVIOUSLY THIS SESSION

### NEW: Prisoner's Dilemma Escalation Game - Complete Interactive Tool
- ✅ **Part I (Basic)** - Complete bilingual implementation
  - English: `prisoners_dilemma_escalation.html`
  - Spanish: `prisoners_dilemma_escalation-es.html`
  - Features: 5-round game, Group A vs Group B dynamics, deterministic opponent behavior
  - Navigation: Top nav (Home/DataLab), end screen buttons (Replay, Perspective, Continue to Part II)
  
- ✅ **Part II (Unpredictable)** - Complete bilingual implementation with noise mechanics
  - English: `prisoners_dilemma_escalation-parte2.html`
  - Spanish: `prisoners_dilemma_escalation-parte2-es.html`
  - Features: Probabilistic opponent behavior (35% misperception shock), internal interests explanation
  - Navigation: Top nav (Home/DataLab), end screen buttons (Replay, Back to Part I, DataLab, Home)
  - Educational content: "Understanding the Noise" section explains competing interests (hardliners, economic actors, intelligence, opposition)
  
- ✅ **Website Integration**
  - Linked from data-lab.html and data-lab-es.html
  - Linked from teaching-es.html (Spanish version)
  - Auto-forward: Part I end screen includes "Continue to Part II" button
  - Cross-navigation: All pages properly linked with Home/DataLab returns

- ✅ **Game Mechanics Verified**
  - Part I: Tit-for-tat opponent (mirrors your last choice)
  - Part II: Probabilistic defection even when cooperating (models internal pressures)
  - Scoring: Proper prisoner's dilemma payoff matrix (3,3 mutual coop; 0,5 sucker; 5,0 temptation; 1,1 mutual defect)
  - UI: Clean history tracking, real-time score updates, narrative progression

### Previous Session: Pillar 02 Algorithmic Governance
- ✅ Website status changed from "Coming Soon" → "Updated" on all 4 pages
- ✅ Links corrected to point to Research-Portfolio standalone repo

## 🔴 CRITICAL: Dead Links & Missing Files

### ✅ FIXED (Jan 11): Blog Post Status
- ✅ "Hello Law!" blog post: Corrected from "Coming Soon" → "poetry" label
- ✅ Blog post already exists with content, so label now reflects reality
- ✅ Post accessible at [blog-posts/01-blog-post-title-here.html](blog-posts/01-blog-post-title-here.html)

### Teaching Resources (Ongoing - Decide by Jan 15)

All course material links point to non-existent files:
- ❌ `pdfs/eu-digital-law.pptx` - **MISSING**
- ❌ `pdfs/peace-innovation.pptx` - **MISSING**
- ❌ `pdfs/peace-innovation-resources.pdf` - **MISSING**

**Current pdfs/ folder only contains:**
- ✅ `CV-26.pdf` (exists)
- ✅ `manifest.json` (exists, but only references `sample-brief.pdf`)
- ❌ `sample-brief.pdf` - **MISSING** (referenced in manifest.json)

**Decision needed:** Upload teaching materials to `/pdfs/` OR remove teaching resource links and direct to Class-Portfolio instead

### ✅ FIXED (Jan 11): Contact Pages Enhanced
- ✅ Added descriptive text to all contact options
- ✅ Email: "Let's do nerdy peace talk" (EN) / "Hagamos conversaciones nerds sobre paz" (ES)
- ✅ GitHub: "Check out my working repositories on research, courses and data experiments" (EN) / "Revisa mis repositorios de investigación, cursos y experimentos de datos" (ES)
- ✅ LinkedIn: "Check my professional profile" (EN) / "Consulta mi perfil profesional" (ES)
- ✅ Pixelfed: "I like taking pictures. This is my portfolio of my life in pictures" (EN) / "Me encanta tomar fotos. Este es mi portafolio de mi vida en imágenes" (ES)
- ✅ Applied to [contact.html](contact.html) and [contact-es.html](contact-es.html)

## 🟡 CONTENT GAPS: Portfolio ↔ Website Mismatches

#### Pillar 01: Technodiversity & Decolonization
- 📂 Location: `Research-Portfolio/01-technodiversity-and-decolonization/`
- ✅ Has: `research-questions.md` (minimal, 3 lines)
- ❌ Missing: Working papers, literature reviews, structural taxonomies (promised in main README)
- 📂 `notes/` folder: **EMPTY**
- 🌐 Website: Links from [index.html](index.html) and [research.html](research.html) labeled "Coming Soon"
- ✅ Has: README, research-questions.md, Spanish working paper, English working paper, populated bibliography
- ✅ NEW: First case study (CNIL vs Google 2022) in case-studies/
- ⚠️ Missing: 3-5 more enforcement case studies, datasets
- 📂 `notes/` folder: ✅ Now populated with substantive content
- 🌐 Website: Marked **Updated** on all pages (index.html, research.html, index-es.html, research-es.html)
- 🔗 Direct links to repo (no separate showcase page needed)

- 🔗 Dead link on [index.html](index.html) Teaching section: Points to `notes/` folder (empty)


**ACTION REQUIRED:**
   - Research notes
2. Add README.md to each pillar directory explaining content/status
### Data Analysis Portfolio - Projects Mostly Empty

- 🌐 Website: **NOT MENTIONED** anywhere on website
- 📝 Status: Exists in repo, absent from website

#### Project 02: Policy Research Tools
- 📂 Location: `Data-Analysis-Portfolio/02-policy-research-tools/`
- ✅ Has: `{notebooks/examples}/` directory
- 🌐 Website: Linked from [index.html](index.html) (#data-lab section)
- 🔗 Link goes to GitHub but directory has no content

#### Project 03: Data Visualization Sub-Projects

**✅ Polarization Spiral** - COMPLETE
- ✅ Has: `data/` folder only
- ❌ Content: **EMPTY**
- 🌐 Website: Marked "Coming Soon" / "In development" on [data-lab.html](data-lab.html)

**⚠️ AI Strategy Explorer (website-only)**
- 🌐 Location: Card on [data-lab.html](data-lab.html) marked "Coming Soon"
- ❌ Folder: **COMPLETELY EMPTY**
- 🌐 Website: **NOT MENTIONED**
2. **Policy Research Tools**: Add example notebooks to `{notebooks/examples}/` directory
3. **Algorithmic Impact Dashboard**: Build out project or remove "Coming Soon" from website

### ✅ PARTIALLY FIXED (Jan 11): Blog Posts
**Location:** `blog-posts/` directory

- ✅ **Post 01 "Hello Law!"** - NOW PUBLISHED with "poetry" label
  - Status changed from "Coming Soon" → "poetry"
  - Content exists at [blog-posts/01-blog-post-title-here.html](blog-posts/01-blog-post-title-here.html)
  - Accessible from [blog.html](blog.html)

- 🔴 **Post 02** - Still placeholder text; marked "Coming Soon"
  - Need to either write content or remove

- 🔴 **Posts 03-04** - Placeholder cards with no actual content
  - All marked "Coming Soon"

**ACTION REQUIRED:**
1. Either write actual blog post content for posts 02, 03, 04
2. Or remove from website listings until ready

### Resources Section (Decide by Jan 15)
## 🔵 WEBSITE ↔ PORTFOLIO CROSS-REFERENCE ISSUES
### Website Links & Content Status

Website link status for all pillars:
1. [01-technodiversity-and-decolonization](https://github.com/juapache/Research-Portfolio/tree/main/01-technodiversity-and-decolonization) - empty notes, minimal research-questions; "Coming Soon" (correct)
2. [02-algorithmic-governance](https://github.com/juapache/Research-Portfolio/tree/main/02-algorithmic-governance) - **Updated**: has working papers + bibliography + literature review + first case study; website status changed to "Updated" (correct)
3. [03-peace-innovation-and-technology](https://github.com/juapache/Research-Portfolio/tree/main/03-peace-innovation-and-technology) - empty notes; "Coming Soon" (correct)
### index.html Teaching Section Dead Links
**Location:** [index.html](index.html) `#teaching` section

Links status:
- ✅ Peace Innovation notes link: Still points to empty folder BUT pillar card is marked "Coming Soon" (acceptable)
- ✅ Algorithmic Governance notes link: Now points to folder WITH content (literature-review.md, research-notes.md)

**Note:** These links are contextually appropriate. Teaching section is marked "Coming Soon" and users understand content is under development.

**ACTION REQUIRED (optional):**
1. Consider updating copy to clarify that these are drafts/works in progress
2. Or promote published notes as "Available: Governance notes now live"

#### Conflict Data Analysis Project
- ✅ Exists in: `Data-Analysis-Portfolio/01-conflict-data-analysis/`
- ❌ Not mentioned anywhere on website
- Structure exists but is empty
- Should this be showcased on [data-lab.html](data-lab.html)?

#### AI Strategy NLP Project (05)
- ✅ **GOOD**: Properly featured on website
- ✅ Has actual content (notebooks, src code, requirements.txt)
- ✅ Linked from [index.html](index.html) hero card

## 🟢 WHAT'S WORKING WELL

1. ✅ **NEW: Prisoner's Dilemma Escalation Game** - Complete interactive teaching tool (Jan 2026)
   - ✅ Part I & II fully functional in EN/ES
   - ✅ Proper game theory mechanics (payoff matrices, probabilistic behavior)
   - ✅ Educational content explaining security dilemma and internal group dynamics
   - ✅ Clean navigation and cross-linking between parts
   - ✅ Integrated into DataLab and Teaching sections

2. ✅ **AI Strategy NLP (05)** - Full implementation, well documented, properly featured on website
   - ✅ Links fixed: now pointing to correct Research-Portfolio repo (not research-workspace)

3. ✅ **Trust Paradox** - Complete with methodology docs, academic references, interactive website page

4. ✅ **Polarization Spiral** - Complete with methodology docs, academic references, interactive website page

5. ✅ **Algorithmic Governance Pillar 02** - Substantive notes, first case study, and working papers
   - Website updated across all 4 pages (EN/ES) to reflect "Updated" status

### Website Infrastructure
- ✅ Clean navigation across all pages
- ✅ Bilingual setup (EN/ES) structured properly with parity
- ✅ SEO metadata in place
- ✅ Proper schema.org markup for search engines
- ✅ Contact page functional with working links
- ✅ About page complete with CV viewer
- ✅ All GitHub links checked and corrected (AI Strategy NLP links fixed)

### Repository Structure
- ✅ Clear separation: Research-Portfolio (conceptual) vs Data-Analysis-Portfolio (technical)
- ✅ Consistent directory naming conventions
- ✅ .gitignore properly configured
- ✅ LICENSE files in place (CC BY-NC 4.0)

---

## 📋 PRIORITIZED ACTION PLAN

### 🔴 **URGENT - Fix Broken Links (Ongoing)**

1. **Teaching Resources** - Still blocking teaching.html credibility
   - [ ] Create or upload 8 teaching files to pdfs/
   - [ ] OR temporarily remove teaching resource download links
   - [ ] Update manifest.json with actual resources
   - [ ] Add sample-brief.pdf or remove from manifest

2. **Blog Post Placeholder** - Blocks blog page usability
   - [ ] OR remove from index.html and blog.html until ready
   - [ ] Fix broken Data Lab nav link in post 02

---
   - **Pillar 02:** Now sufficient; "Updated" reflects live state

   - [ ] Consider sectoral case studies (fintech, employment)

5. **Policy Research Tools (02)** - Empty directory blocks credibility
   - [ ] Add example notebooks to {notebooks/examples}/
   - [ ] Create README explaining usage
   - [ ] Add at least 2-3 practical examples

6. **Resources Section** - Empty until populated
   - [ ] Add actual downloadable resources to pdfs/
   - [ ] Update manifest.json
   - [ ] Test JavaScript resource loading
   - [ ] OR remove section until populated

---

### � SUMMARY STATISTICS

### Content Status Overview (Updated Jan 7, 2026)
- **Interactive Games:** ✅ **NEW: Prisoner's Dilemma (Part I & II)** - 100% complete, bilingual
- **Research Pillar 01:** Minimal (research questions only) — "Coming Soon"
- **Research Pillar 02:** ✅ **Updated** (structure + working papers + bibliography + notes + 1 case study)
- **Research Pillars 03-04:** Empty (notes only) — "Coming Soon"
- **Research Pillar 05 (AI Strategy NLP):** ~90% complete + links fixed
- **Data Viz - Trust Paradox:** 100% complete
- **Data Viz - Polarization Spiral:** 100% complete
- **Data Viz - Algorithmic Dashboard:** 5% complete (folder only)
- **Data Viz - Policy Landscape Maps:** 0% complete (empty)
- **Conflict Data Analysis:** 0% complete (structure only)
- **Policy Research Tools:** 0% complete (empty)
### Broken Links Count
- **Dead PDF file links:** 9 (8 teaching PDFs + 1 sample brief)
- **Links to empty directories:** Now 1 (only Peace Innovation teaching link; Governance link now has content)
- **Incorrect GitHub paths:** ✅ FIXED (AI Strategy NLP was pointing to research-workspace; now correct)
- **Placeholder content items:** Multiple (blog post 02, resources section, AI Strategy Explorer, etc.)
- ⚠️ **Pages with issues:** teaching, data-lab, index, blog (due to placeholders/empty directories)

---

## 🎯 RECOMMENDED NEXT STEPS

**For immediate impact:**
1. **Expand Pillar 02 case studies** (1-2 weeks) — 4-5 more enforcement cases would strengthen credibility
2. **Add Policy Research Tools examples** (1 week) — makes the GitHub link meaningful
3. **Fix teaching resources or remove links** (depends on priority) — unblocks teaching.html

**For portfolio coherence:**
4. **Add README to Pillars 01, 03, 04** explaining scope/status (1 week)
5. **Complete or remove Blog Post 02** (depends on schedule)

**For polish:**
6. Consider adding "Last Updated" dates to research cards
7. Add project status badges (Complete, In Progress, Planned) for clarity

---

## ✅ SESSION SUMMARY (January 7, 2026)

This session accomplished:
- ✅ **Created complete Prisoner's Dilemma teaching game** with Part I (basic) and Part II (unpredictable/noise)
  - Built bilingual versions (EN/ES) for both parts
  - Implemented proper game theory mechanics with probabilistic opponent behavior
  - Added educational content explaining security dilemma and internal group dynamics
  - Integrated navigation across all four game pages and main website
  - Added top navigation (Home/DataLab) and comprehensive end-screen buttons
  - Verified all links and cross-references work correctly

- ✅ **Enhanced DataLab presence** - New interactive game adds to portfolio of teaching tools
- ✅ **Improved teaching resources** - Prisoner's Dilemma now linked from teaching-es.html

**Previous session (Jan 4):**
- ✅ Elevated Pillar 02 from "Coming Soon" → "Updated" with real content
- ✅ Fixed broken AI Strategy NLP links (all 4 pages)
- ✅ Fixed "Coming Soon" badge CSS wrapping issue

**Result:** Website now features three complete interactive visualizations (Trust Paradox, Polarization Spiral, Prisoner's Dilemma) demonstrating technical capabilities and pedagogical approach. DataLab section significantly strengthened.
   - [ ] If removing: Delete empty structure

8. **Algorithmic Impact Dashboard** - Empty project
   - [ ] Decide: Build OR remove "Coming Soon" from website
   - [ ] If building: Create implementation timeline
   - [ ] If removing: Delete from data-lab.html

9. **Policy Landscape Maps** - Completely empty
   - [ ] Decide: Keep folder OR develop project
   - [ ] If removing: Delete directory

---

### 🟢 **POLISH & ENHANCEMENT (Ongoing)**

10. **Documentation** - UPDATED
    - [x] Pillar 02 now has comprehensive README and notes
    - [x] Completed projects have proper README files
    - [ ] Add inline code comments to src/ modules
    - [ ] Update main portfolio READMEs with current status

11. **Website Enhancements** - UPDATED THIS SESSION
    - [x] Fix "Coming Soon" badge wrapping (CSS: white-space: nowrap)
    - [x] Fix broken AI Strategy NLP GitHub links (all 4 pages)
    - [x] Update Pillar 02 website status (all 4 pages: index, research, and ES versions)
    - [ ] Add "Last Updated" dates to project cards
    - [ ] Consider adding project status badges (Complete, In Progress, Planned)

12. **Spanish Translations** - ✅ UPDATED
    - [x] Pillar 02 "Actualizado" tag on research-es.html and index-es.html
    - [x] All EN/ES page pairs aligned
    - [ ] Verify other -es.html pages maintain full content parity

6. **Resources Section**
   - [ ] Add actual downloadable resources to pdfs/
   - [ ] Update manifest.json
   - [ ] Test JavaScript resource loading
   - [ ] OR remove/keep labeled "Coming Soon" until populated

---

### 🔵 **MEDIUM PRIORITY - Strategic Decisions (Weeks 5-8)**

7. **Conflict Data Analysis (01)**
   - [ ] Decide: Develop this project OR deprioritize
   - [ ] If keeping: Add to website Data Lab section
   - [ ] If developing: Populate directories with notebooks/data
   - [ ] If removing: Delete empty structure

8. **Algorithmic Impact Dashboard**
   - [ ] Decide: Build it OR remove "Coming Soon"
   - [ ] If building: Create implementation timeline
   - [ ] If removing: Delete from data-lab.html

9. **Policy Landscape Maps**
   - [ ] Decide: Keep empty folder OR develop project
   - [ ] If developing: Add to website
   - [ ] If removing: Delete directory

---

### 🟢 **POLISH & ENHANCEMENT (Ongoing)**

10. **Documentation**
    - [ ] Ensure all completed projects have proper README files
    - [ ] Add inline code comments to src/ modules
    - [ ] Update main portfolio READMEs with current status

11. **Website Enhancements**
    - [ ] Add "Last Updated" dates to project cards
    - [ ] Consider adding project status badges (Complete, In Progress, Planned)
    - [ ] Ensure all external GitHub links work correctly

12. **Spanish Translations**
    - [ ] Verify all -es.html pages are properly translated
    - [ ] Ensure content parity between EN/ES versions

---

## 📊 SUMMARY STATISTICS

### Content Status Overview
- **Research Pillar 01:** Minimal (research questions only)
- **Research Pillar 02:** Partial (structure + Spanish & English working papers + bibliography; notes/case studies missing)
- **Research Pillars 03-04:** Empty (notes only)
- **Research Pillar 05 (AI Strategy NLP):** ~90% complete
- **Data Viz - Trust Paradox:** 100% complete
- **Data Viz - Polarization Spiral:** 100% complete
- **Data Viz - Algorithmic Dashboard:** 5% complete (folder only)
- **Data Viz - Policy Landscape Maps:** 0% complete (empty)
- **Conflict Data Analysis:** 0% complete (structure only)
- **Policy Research Tools:** 0% complete (empty)
- **AI Strategy Explorer:** 0% (website-only placeholder)

### Broken Links Count
- **Dead file links:** 9 (8 teaching PDFs + 1 sample brief)
- **Links to empty directories:** 4 (research pillar notes folders)
- **Placeholder content items:** Multiple (blog cards, resources section, manifest.json, AI Strategy Explorer card, Policy Research Tools card)

### Website Completeness (Updated Jan 7, 2026)
- ✅ **Fully functional pages:** about, contact, trust-paradox, polarization-spiral, prisoners_dilemma_escalation (all parts), AI Strategy NLP linkages
- ⚠️ **Pages with minor issues:** data-lab (some "Coming Soon" projects), teaching (missing downloadable materials)
- 🔴 **Pages with broken links:** teaching (8 missing downloads), index (resources empty)
- ✅ **Interactive tools count:** 3 complete (Trust Paradox, Polarization Spiral, Prisoner's Dilemma with 4 total pages)

---

## 🎯 RECOMMENDED FOCUS

**For website finalization, prioritize in this order:**

1. **Fix teaching.html** - Either upload teaching materials OR remove download links
2. **Complete/remove blog post 02** - Eliminate placeholder content
3. **Populate Research Pillars 01-04** - Add at least basic README and initial notes
4. **Add Policy Research Tools examples** - Make the link from website meaningful
5. **Strategic decision on incomplete projects** - Commit to building OR remove from website

**Timeline Estimate:**
- Critical fixes (broken links): 1-2 days
- Content development (pillars): 2-4 weeks
- Strategic decisions: 1 week for planning
- Full portfolio completion: 6-8 weeks

---

## 📝 NOTES

- Main README claims "working papers" exist but none are present in repositories
- Website promises "reproducible tools" but most tool directories are empty
- The gap between promised content and actual content is significant
- AI Strategy NLP (05) is the model for what other projects should look like
- Consider being transparent on website about which projects are "In Development" vs "Complete"

---

**END OF REPORT**
