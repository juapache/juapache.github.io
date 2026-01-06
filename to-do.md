# Website & Portfolio To-Do List
**Status Report: juapache.github.io + Research-Portfolio + Data-Analysis-Portfolio**  
**Last Audit:** January 4, 2026 (Updated after session edits)

---
## ✅ UPDATES COMPLETED THIS SESSION

### Pillar 02: Algorithmic Governance - Now Live
- ✅ Website status changed from "Coming Soon" → "Updated" on all 4 pages (index.html, research.html, index-es.html, research-es.html)
  - Changed to: `github.com/juapache/Research-Portfolio/tree/main/05-ai-strategy-nlp`
  - Reason: Research-Portfolio is a standalone repo, not nested under research-workspace

## 🔴 CRITICAL: Dead Links & Missing Files

### Teaching Resources (All Missing)

All course material links point to non-existent files:
- ❌ `pdfs/eu-digital-law.pptx` - **MISSING**
- ❌ `pdfs/peace-innovation.pptx` - **MISSING**
- ❌ `pdfs/peace-innovation-resources.pdf` - **MISSING**

**Current pdfs/ folder only contains:**
- ✅ `CV-26.pdf` (exists)
- ✅ `manifest.json` (exists, but only references `sample-brief.pdf`)
- ❌ `sample-brief.pdf` - **MISSING** (referenced in manifest.json)

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
**Location:** `blog-posts/` directory

- 🔴 Content: Placeholder text; marked "Coming Soon" on blog listing and post header
- 🌐 Linked from: [index.html](index.html) and [blog.html](blog.html)
- Additional placeholder cards on [blog.html](blog.html) (no target links or `#` anchors) all marked "Coming Soon"

**ACTION REQUIRED:**
1. Either write actual blog post content for post 02
2. Or remove from website listings until ready
**Location:** [index.html](index.html) `#resources` section


**ACTION REQUIRED:**
1. Add actual resources to pdfs/ folder
2. Update manifest.json with real resource metadata
3. Ensure JavaScript properly loads and displays resources
4. Or remove empty section from index.html

---

**ACTION REQUIRED:**
- Either develop course materials
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

1. ✅ **AI Strategy NLP (05)** - Full implementation, well documented, properly featured on website
   - ✅ Links fixed: now pointing to correct Research-Portfolio repo (not research-workspace)
2. ✅ **Trust Paradox** - Complete with methodology docs, academic references, interactive website page
3. ✅ **Polarization Spiral** - Complete with methodology docs, academic references, interactive website page
4. ✅ **Algorithmic Governance Pillar 02** - NEW: Now has substantive notes, first case study, and working papers
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

### Content Status Overview (Updated)
- **Research Pillar 02:** ✅ **Updated** (structure + working papers + bibliography + notes + 1 case study)
- **Research Pillars 03-04:** Empty (notes only) — "Coming Soon"
- **Research Pillar 05 (AI Strategy NLP):** ~90% complete + links fixed
- **Data Viz - Trust Paradox:** 100% complete
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

## ✅ SESSION SUMMARY

This session accomplished:
- ✅ Elevated Pillar 02 from "Coming Soon" → "Updated" with real content (notes + case study)
- ✅ Fixed broken AI Strategy NLP links (all 4 pages)
- ✅ Fixed "Coming Soon" badge CSS wrapping issue
- ✅ Updated ES website pages to match EN updates

**Result:** Website more accurately reflects portfolio state; Pillar 02 now has sufficient substance to justify "Updated" tag. Two major blockers remain: teaching PDFs and blog post placeholder.
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

### Website Completeness
- ✅ **Fully functional pages:** about, contact, trust-paradox, polarization-spiral, AI Strategy NLP linkages
- ⚠️ **Pages with issues:** teaching, data-lab, research, index, blog (due to placeholders/empty downloads)
- 🔴 **Pages with broken links:** teaching (8 missing downloads), index (resources empty, links to empty notes folders)

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
