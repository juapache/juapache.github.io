# Website & Portfolio To-Do List
**Status Report: juapache.github.io + Research-Portfolio + Data-Analysis-Portfolio**  
**Generated:** January 4, 2026

---

## 🔴 CRITICAL: Dead Links & Missing Files

### Teaching Resources (All Missing)
**Location:** [teaching.html](teaching.html)

All course material links point to non-existent files:
- ❌ `pdfs/peace-conflict-studies.pptx` - **MISSING**
- ❌ `pdfs/peace-conflict-resources.pdf` - **MISSING**
- ❌ `pdfs/negotiation-skills.pptx` - **MISSING**
- ❌ `pdfs/negotiation-resources.pdf` - **MISSING**
- ❌ `pdfs/eu-digital-law.pptx` - **MISSING**
- ❌ `pdfs/eu-digital-resources.pdf` - **MISSING**
- ❌ `pdfs/peace-innovation.pptx` - **MISSING**
- ❌ `pdfs/peace-innovation-resources.pdf` - **MISSING**

**Current pdfs/ folder only contains:**
- ✅ `CV-26.pdf` (exists)
- ✅ `manifest.json` (exists, but only references `sample-brief.pdf`)
- ❌ `sample-brief.pdf` - **MISSING** (referenced in manifest.json)

**ACTION REQUIRED:**
1. Either create/upload all 8 teaching resource files
2. Or remove the dead links from teaching.html
3. Add actual teaching materials to pdfs/ folder
4. Update manifest.json with real resource metadata

---

## 🟡 CONTENT GAPS: Portfolio ↔ Website Mismatches

### Research Portfolio - Pillars 01-04 (mixed progress)
**Status:** Pillar 02 now has structure, research questions, Spanish working paper, and bibliography; Pillars 01/03/04 remain effectively empty.

#### Pillar 01: Technodiversity & Decolonization
- 📂 Location: `Research-Portfolio/01-technodiversity-and-decolonization/`
- ✅ Has: `research-questions.md` (minimal, 3 lines)
- ❌ Missing: Working papers, literature reviews, structural taxonomies (promised in main README)
- 📂 `notes/` folder: **EMPTY**
- 🌐 Website: Links from [index.html](index.html) and [research.html](research.html) labeled "Coming Soon"

#### Pillar 02: Algorithmic Governance
- 📂 Location: `Research-Portfolio/02-algorithmic-governance/`
- ✅ Has: README, research-questions.md, Spanish working paper, English working paper, populated bibliography, case-study template
- ⚠️ Missing: More case studies (1 added), datasets
- 📂 `notes/` folder: literature review + research notes now present
- 🌐 Website: Marked **Updated** on [index.html](index.html) and [research.html](research.html); both link directly to the repo instead of a new page; ES pages also updated

#### Pillar 03: Peace Innovation & Technology
- 📂 Location: `Research-Portfolio/03-peace-innovation-and-technology/`
- ❌ Missing: All content
- 📂 `notes/` folder: **EMPTY**
- 🌐 Website: Links from [index.html](index.html) and [research.html](research.html) labeled "Coming Soon"
- 🔗 Dead link on [index.html](index.html) Teaching section: Points to `notes/` folder (empty)

#### Pillar 04: Global South Perspectives
- 📂 Location: `Research-Portfolio/04-global-south-perspectives/`
- ❌ Missing: All content
- 📂 `notes/` folder: **EMPTY**
- 🌐 Website: Links from [index.html](index.html) and [research.html](research.html) labeled "Coming Soon"

**ACTION REQUIRED:**
1. Populate each pillar with promised content:
   - Working papers (mentioned in main README)
   - Literature reviews
   - Structural taxonomies
   - Research notes
2. Add README.md to each pillar directory explaining content/status
3. Consider adding "Under Development" badges to website cards if content isn't ready

---

### Data Analysis Portfolio - Projects Mostly Empty

#### Project 01: Conflict Data Analysis
- 📂 Location: `Data-Analysis-Portfolio/01-conflict-data-analysis/`
- ✅ Has: Directory structure (data/, notebooks/, results/, src/)
- ❌ All subdirectories: **EMPTY**
- 🌐 Website: **NOT MENTIONED** anywhere on website
- 📝 Status: Exists in repo, absent from website

#### Project 02: Policy Research Tools
- 📂 Location: `Data-Analysis-Portfolio/02-policy-research-tools/`
- ✅ Has: `{notebooks/examples}/` directory
- ❌ Directory: **EMPTY**
- 🌐 Website: Linked from [index.html](index.html) (#data-lab section)
- 🔗 Link goes to GitHub but directory has no content

#### Project 03: Data Visualization Sub-Projects

**✅ Trust Paradox** - COMPLETE
- Has full documentation (README, METHODOLOGY, ACADEMIC_REFERENCES, etc.)
- ✅ Website integration: [trust-paradox.html](trust-paradox.html) exists

**✅ Polarization Spiral** - COMPLETE
- Has full documentation (README, METHODOLOGY, ACADEMIC_REFERENCES, etc.)
- ✅ Website integration: [polarization-spiral.html](polarization-spiral.html) exists

**⚠️ Algorithmic Impact Dashboard**
- 📂 Location: `Data-Analysis-Portfolio/03-data-visualization/algorithmic-impact-dashboard/`
- ✅ Has: `data/` folder only
- ❌ Content: **EMPTY**
- 🌐 Website: Marked "Coming Soon" / "In development" on [data-lab.html](data-lab.html)

**⚠️ AI Strategy Explorer (website-only)**
- 🌐 Location: Card on [data-lab.html](data-lab.html) marked "Coming Soon"
- ❌ No corresponding project folder/repo yet

**❌ Policy Landscape Maps**
- 📂 Location: `Data-Analysis-Portfolio/03-data-visualization/policy-landscape-maps/`
- ❌ Folder: **COMPLETELY EMPTY**
- 🌐 Website: **NOT MENTIONED**

**ACTION REQUIRED:**
1. **Conflict Data Analysis**: Either populate with content OR document on website as "forthcoming"
2. **Policy Research Tools**: Add example notebooks to `{notebooks/examples}/` directory
3. **Algorithmic Impact Dashboard**: Build out project or remove "Coming Soon" from website
4. **Policy Landscape Maps**: Either develop project or remove empty directory

---

## 🟡 PLACEHOLDER CONTENT

### Blog Posts
**Location:** `blog-posts/` directory

#### Blog Post 02: Template Placeholder
- 📄 File: `blog-posts/02-another-blog-post-title.html`
- 🔴 Title: "Another Blog Post Title" (generic placeholder)
- 🔴 Date: "[Date]" (placeholder text)
- 🔴 Content: Placeholder text; marked "Coming Soon" on blog listing and post header
- 🌐 Linked from: [index.html](index.html) and [blog.html](blog.html)
- ⚠️ Navigation issue: Data Lab link uses `<span class="nav-muted">` instead of proper `<a>` tag

#### Other blog placeholders
- Additional placeholder cards on [blog.html](blog.html) (no target links or `#` anchors) all marked "Coming Soon"
- "Hello Law!" is also tagged "Coming Soon" though content exists

**ACTION REQUIRED:**
1. Either write actual blog post content for post 02
2. Or remove from website listings until ready
3. Fix broken Data Lab navigation link in blog post 02

---

### Website Resources Section
**Location:** [index.html](index.html) `#resources` section

- Section header exists: "Resources - Downloadable briefs, lecture decks, and other resources"
- Content area: `<ul id="resources-list" class="link-list"></ul>` - **EMPTY** (labeled "Coming Soon")
- Appears to expect JavaScript to populate from `pdfs/manifest.json`
- Current manifest.json only has placeholder: `sample-brief.pdf` (which doesn't exist)

**ACTION REQUIRED:**
1. Add actual resources to pdfs/ folder
2. Update manifest.json with real resource metadata
3. Ensure JavaScript properly loads and displays resources
4. Or remove empty section from index.html

---

### Teaching Page - "Coming Soon" Course
**Location:** [teaching.html](teaching.html)

- Course 5: "Positive Peace Systems" - marked `<span class="tag small">Coming Soon</span>`
- Card styled with `opacity: 0.5;` to indicate unavailable
- No links (appropriate for coming soon status)
- Tagged with `#IEP` (Institute for Economics and Peace)

**ACTION REQUIRED:**
- Either develop course materials
- Or keep as-is (properly marked as future content)

---

## 🔵 WEBSITE ↔ PORTFOLIO CROSS-REFERENCE ISSUES

### Website Links to Empty GitHub Directories

Website links now labeled "Coming Soon" for all pillars; content status:
1. [01-technodiversity-and-decolonization](https://github.com/juapache/research-workspace/tree/main/Research-Portfolio/01-technodiversity-and-decolonization) - empty notes, minimal research-questions
2. [02-algorithmic-governance](https://github.com/juapache/research-workspace/tree/main/Research-Portfolio/02-algorithmic-governance) - structure + Spanish working paper + bibliography; notes/case studies pending
3. [03-peace-innovation-and-technology](https://github.com/juapache/research-workspace/tree/main/Research-Portfolio/03-peace-innovation-and-technology) - empty notes
4. [04-global-south-perspectives](https://github.com/juapache/research-workspace/tree/main/Research-Portfolio/04-global-south-perspectives) - empty notes

### index.html Teaching Section Dead Links
**Location:** [index.html](index.html) `#teaching` section

Links point to empty notes folders:
- `https://github.com/juapache/research-workspace/tree/main/Research-Portfolio/03-peace-innovation-and-technology/notes` - **EMPTY FOLDER**
- `https://github.com/juapache/research-workspace/tree/main/Research-Portfolio/02-algorithmic-governance/notes` - **EMPTY FOLDER**

**ACTION REQUIRED:**
1. Populate notes folders with seminar notes/readings
2. Or remove these specific links from index.html until content exists

---

### Portfolio Content Not on Website

#### Conflict Data Analysis Project
- ✅ Exists in: `Data-Analysis-Portfolio/01-conflict-data-analysis/`
- ❌ Not mentioned anywhere on website
- Structure exists but is empty
- Should this be showcased on [data-lab.html](data-lab.html)?

#### AI Strategy NLP Project (05)
- ✅ **GOOD**: Properly featured on website
- ✅ Has actual content (notebooks, src code, requirements.txt)
- ✅ Linked from [index.html](index.html) hero card
- ✅ Mentioned on [research.html](research.html)
- ✅ This is the ONLY fully developed project besides Trust Paradox & Polarization Spiral

---

## 🟢 WHAT'S WORKING WELL

### Properly Integrated Projects
1. ✅ **AI Strategy NLP (05)** - Full implementation, well documented, properly featured on website
2. ✅ **Trust Paradox** - Complete with methodology docs, academic references, interactive website page
3. ✅ **Polarization Spiral** - Complete with methodology docs, academic references, interactive website page

### Website Infrastructure
- ✅ Clean navigation across all pages
- ✅ Bilingual setup (EN/ES) structured properly
- ✅ SEO metadata in place
- ✅ Proper schema.org markup for search engines
- ✅ Contact page functional with working links
- ✅ About page complete with CV viewer
- ✅ "Coming Soon" badges no longer wrap to two lines (nowrap styling added)

### Repository Structure
- ✅ Clear separation: Research-Portfolio (conceptual) vs Data-Analysis-Portfolio (technical)
- ✅ Consistent directory naming conventions
- ✅ .gitignore properly configured
- ✅ LICENSE files in place (CC BY-NC 4.0)

---

## 📋 PRIORITIZED ACTION PLAN

### 🔴 **URGENT - Fix Broken Links (Week 1)**

1. **Teaching Resources**
   - [ ] Create or upload 8 teaching files to pdfs/
   - [ ] OR temporarily remove teaching resource download links
   - [ ] Update manifest.json with actual resources
   - [ ] Add sample-brief.pdf or remove from manifest

2. **Blog Post Placeholder**
   - [ ] Complete blog-posts/02-another-blog-post-title.html with real content
   - [ ] OR remove from index.html and blog.html until ready
   - [ ] Fix broken Data Lab nav link in post 02

3. **Empty Notes Folder Links**
   - [ ] Remove teaching section links from index.html
   - [ ] OR add actual content to notes/ folders

---

### 🟡 **HIGH PRIORITY - Content Development (Weeks 2-4)**

4. **Research Pillars 01-04**
   - [ ] Add README.md to 01/03/04 explaining scope/status
   - [ ] Populate 01/03/04 with initial working papers or literature reviews
   - [ ] Add research notes to notes/ folders (all pillars)
   - [ ] Pillar 02: expand case studies (1 added) and add datasets; site tag set to **Updated** with direct repo link (EN/ES)

5. **Policy Research Tools (02)**
   - [ ] Add example notebooks to {notebooks/examples}/
   - [ ] Create README explaining usage
   - [ ] Add at least 2-3 practical examples

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
