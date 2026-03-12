# ☁️ SFDC Admin Master Hub

> A single-stop, interactive reference guide covering every concept from the **Salesforce Admin Beginner's Trail** — built for quick revision, deep learning, and interview preparation.

---

## 📌 Overview

The **SFDC Admin Master Hub** is a fully self-contained HTML application that requires no internet connection, no framework, and no installation. Just open the file in any browser and start learning.

It was built as a personal study companion for anyone working toward a **Salesforce Administrator** or **Salesforce Platform Developer** role — covering all core Admin concepts in depth with interactive quizzes, a live search engine, and a quick-access cheat sheet.

---

## ✨ Features

| Feature | Description |
|---|---|
| 🔍 **Global Search** | Instantly search any concept, term, or keyword across all 76 topics |
| 📖 **Expandable Concept Blocks** | Click to expand each concept for a deep-dive explanation |
| 🎯 **Practice Quizzes** | One quiz per module to test your understanding with instant feedback |
| ⚡ **Quick Cheat Sheet** | All key facts, limits, and distinctions summarised on one page |
| 📊 **Progress Tracker** | Sidebar tracker that marks which topics you have visited |
| 💡 **Tip / Note / Warning Boxes** | Colour-coded callouts highlighting critical points throughout |
| 📱 **No Dependencies** | Pure HTML, CSS, and JavaScript — works offline in any browser |

---

## 📚 Modules Covered

The hub covers **10 core modules** with **76 total concepts**:

1. **☁️ Platform Basics** — Salesforce architecture, cloud products, editions, orgs, and core terminology
2. **🗄️ Data Model** — Objects, field types, relationships (Master-Detail, Lookup, Many-to-Many), and Schema Builder
3. **🔐 Security & Access** — The 4-layer security model, Profiles, Permission Sets, Roles, OWD, and Sharing Rules
4. **⚙️ Automation** — Flow Builder (all flow types), Process Builder, Workflow Rules, and Approval Processes
5. **✅ Validation & Formula** — Validation rule logic, formula functions reference, formula fields vs roll-up summaries
6. **📊 Reports & Dashboards** — All 4 report types, filters, bucket fields, dashboard components, and dynamic dashboards
7. **💼 Sales Cloud** — The full sales cycle, Leads, Opportunities, Products, Price Books, and pipeline management
8. **🎧 Service Cloud** — Cases, Queues, Assignment Rules, Escalation Rules, Knowledge, Entitlements, and Omni-Channel
9. **📦 Data Management** — Import Wizard vs Data Loader, Duplicate Management, Data Export, and backup strategies
10. **🧩 App Builder & UI** — Lightning App Builder, Page Layouts vs Lightning Pages, Quick Actions, Compact Layouts, and List Views

---

## 🚀 How to Use

### Option A — Open Locally
1. Download `SFDC_Admin_MasterHub.html`
2. Double-click to open it in your browser
3. No setup required — it works completely offline

### Option B — Host Online (Netlify Drop — Easiest)
1. Go to [netlify.com/drop](https://netlify.com/drop)
2. Rename the file to `index.html`
3. Drag and drop the file onto the Netlify Drop page
4. Your hub is instantly live at a public URL

### Option C — Host on GitHub Pages (Recommended for permanence)
1. Create a free account at [github.com](https://github.com)
2. Create a new repository (e.g. `sfdc-admin-hub`)
3. Upload the file renamed as `index.html`
4. Go to **Settings → Pages → Source → main branch → Save**
5. Your hub goes live at `https://yourusername.github.io/sfdc-admin-hub`

---

## 🗂️ Repository Structure

```
sfdc-admin-hub/
│
├── index.html          # The complete Master Hub (single file application)
└── README.md           # This file
```

> The entire application lives in a single HTML file — no separate CSS files, JS files, or build steps needed.

---

## 🎯 Who Is This For?

- **Salesforce Admin Beginners** who have completed or are working through the Trailhead Admin Beginner Trail
- **Aspiring Salesforce Developers** who need a solid Admin foundation before diving into Apex and LWC
- **ADM 201 Certification Candidates** using this as a revision companion
- **Anyone returning to Salesforce** after a break who needs a quick refresher

---

## 🧠 How to Study With This Hub

**For daily revision:**
> Use the **Search bar** to look up specific concepts as they come up during practice or work.

**For structured learning:**
> Work through each module in the sidebar from top to bottom, opening every concept block and completing the quiz before moving on.

**For exam/interview prep:**
> Open the **⚡ Quick Cheat Sheet** from the sidebar and review the key distinctions, limits, and comparisons.

**For quick lookups:**
> Use the search — type any keyword like "OWD", "Roll-Up", "Master-Detail" or "Flow" to jump directly to the relevant content.

---

## 📝 Key Concepts Quick Reference

### The Most Important Distinctions to Remember

```
Profile   → Controls WHAT you can DO  (object & field permissions)
Role      → Controls WHAT you can SEE (record visibility)

Master-Detail → Tight relationship. Child deleted when parent deleted.
Lookup        → Loose relationship. Child exists independently.

OWD           → Set as RESTRICTIVE as possible (the floor)
Sharing Rules → Used to OPEN access above OWD (never restrict)

Flow Builder  → Current standard automation tool (use this)
Process Builder / Workflow Rules → Being retired (migrate to Flow)

Validation Rule formula → Returns TRUE when there is an ERROR
```

### Critical Limits

| Item | Limit |
|---|---|
| Master-Detail Relationships per Object | 2 |
| Lookup Relationships per Object | 40 |
| Custom Fields per Object | 500 |
| Dashboard Components per Dashboard | 20 |
| Cross-Object Formula Depth | 10 levels |
| Import Wizard Max Records | 50,000 |
| Joined Report Blocks | 5 |

---

## 🛣️ What's Next After Admin?

Once you are comfortable with all Admin concepts, the recommended path toward a **Salesforce Developer role** is:

1. **Platform Developer I (PDI) Trail** on Trailhead
2. Learn **Apex** — Salesforce's Java-like programming language
3. Learn **SOQL** — Salesforce Object Query Language
4. Learn **Lightning Web Components (LWC)** — modern UI development
5. Practice in a free **Developer Org** at [developer.salesforce.com](https://developer.salesforce.com)
6. Target the **Salesforce Platform Developer I Certification**

---

## 🙏 Acknowledgements

Built as a personal learning project after completing the **Salesforce Admin Beginner's Trail on Trailhead**. All content is based on official Salesforce documentation and Trailhead learning material.

---

## 📄 License

This project is for **personal educational use**. Salesforce, Trailhead, and all related marks are trademarks of Salesforce, Inc.

---

<p align="center">Made with 💙 for the Salesforce learning community</p>
<p align="center">☁️ Keep learning. Keep building. Keep trailblazing.</p>
