# Graph Report - xtendm3-master  (2026-10-01)

## Corpus Check
- 171 files · ~145,235 words
- Verdict: corpus is large enough that graph structure adds value.

## Summary
- 193 nodes · 199 edges · 27 communities (19 shown, 8 thin omitted)
- Extraction: 48% EXTRACTED · 52% INFERRED · 0% AMBIGUOUS · INFERRED: 104 edges (avg confidence: 0.98)
- Token cost: 0 input · 0 output

## Community Hubs (Navigation)
- Build & Project Config
- XtendM3 Core APIs
- Session & Batch Services
- Development Dependencies
- NPM Packages
- Theme Stylesheets
- Site Layout & Templates
- Site Navigation
- Package Metadata
- Theme JavaScript
- Getting Started Guides
- Database APIs
- Dark Mode & UI
- Jekyll Configuration
- Repository Info
- Visual Assets
- Build Scripts
- M3 Platform
- Site Title Config
- Doc Guidelines
- Code Examples
- Dependency Management

## God Nodes (most connected - your core abstractions)
1. `XtendM3 Capabilities Documentation` - 15 edges
2. `API Specification Overview` - 11 edges
3. `Programming Standards` - 8 edges
4. `_requested` - 7 edges
5. `Default Layout Template` - 5 edges
6. `Database API` - 5 edges
7. `Interactive Extension` - 5 edges
8. `Trigger Extension` - 5 edges
9. `Batch Extension` - 5 edges
10. `ignoreFiles` - 4 edges

## Surprising Connections (you probably didn't know these)
- `404 Error Page` --references--> `Default Layout Template`  [INFERRED]
  404.html → _layouts/default.html
- `Default Layout Template` --calls--> `Head Include Template`  [INFERRED]
  _layouts/default.html → _includes/head.html
- `Default Layout Template` --calls--> `Navigation Include Template`  [INFERRED]
  _layouts/default.html → _includes/nav.html
- `Default Layout Template` --calls--> `Site Title Include`  [INFERRED]
  _layouts/default.html → _includes/title.html
- `XtendM3` --references--> `Jekyll Configuration`  [INFERRED]
  README.md → _config.yml

## Import Cycles
- None detected.

## Communities (27 total, 8 thin omitted)

### Community 0 - "Build & Project Config"
Cohesion: 0.05
Nodes (41): #DEV:/, normalize.scss, _args, author, bugs, url, dependencies, description (+33 more)

### Community 1 - "XtendM3 Core APIs"
Cohesion: 0.10
Nodes (28): DatabaseAPI, ION API, LoggerAPI, MICaller API, TextFiles API, Batch Extension, Dynamic Table, Experience Designer (+20 more)

### Community 2 - "Session & Batch Services"
Cohesion: 0.14
Nodes (20): MIAPI, SessionAPI, Batch Scheduling Guide, XtendM3 Development Process, Extension Templates, XtendM3 Activation Process, Extension Points, Batch Extension (+12 more)

### Community 3 - "Development Dependencies"
Cohesion: 0.13
Nodes (15): devDependencies, prettier, @primer/css, stylelint, stylelint-config-prettier, stylelint-config-primer, stylelint-prettier, stylelint-selector-no-utility (+7 more)

### Community 4 - "NPM Packages"
Cohesion: 0.17
Nodes (11): bugs, dependencies, description, license, name, repository, scripts, format (+3 more)

### Community 5 - "Theme Stylesheets"
Cohesion: 0.17
Nodes (11): assets/css/dark-mode-preview.scss, assets/css/just-the-docs.scss, _sass/vendor/**/*.scss, stylelint-config-prettier, stylelint-config-primer, stylelint-prettier, extends, ignoreFiles (+3 more)

### Community 6 - "Site Layout & Templates"
Cohesion: 0.20
Nodes (10): 404 Error Page, Jekyll Site Configuration, Custom Head Include, Head Include Template, Navigation Include Template, Site Title Include, Jekyll Static Site Generator, Just the Docs Theme (+2 more)

### Community 7 - "Site Navigation"
Cohesion: 0.33
Nodes (7): Search Icon, Just The Docs JavaScript, addEvent, initNav, initSearch, searchResults, Lunr Search Library

### Community 8 - "Package Metadata"
Cohesion: 0.29
Nodes (7): _requested, name, raw, rawSpec, scope, spec, type

### Community 10 - "Getting Started Guides"
Cohesion: 0.40
Nodes (5): ACME Corp Extensions Template, Version Control Guidelines, Getting Started, Git Version Control, Maven Build System

### Community 11 - "Database APIs"
Cohesion: 0.60
Nodes (5): DBAction API, DBContainer API, ExpressionFactory API, LockedResult API, Database API

### Community 12 - "Dark Mode & UI"
Cohesion: 0.50
Nodes (4): Just The Docs Image, Dark Mode Preview Script, toggleDarkMode, updateButtonText

### Community 13 - "Jekyll Configuration"
Cohesion: 0.67
Nodes (3): Jekyll Configuration, Just the Docs Theme, XtendM3

### Community 14 - "Repository Info"
Cohesion: 0.67
Nodes (3): repository, type, url

## Knowledge Gaps
- **109 isolated node(s):** `assets/css/just-the-docs.scss`, `assets/css/dark-mode-preview.scss`, `_sass/vendor/**/*.scss`, `stylelint-config-primer`, `stylelint-config-prettier` (+104 more)
  These have ≤1 connection - possible missing edges or undocumented components.
- **8 thin communities (<3 nodes) omitted from report** — run `graphify query` to explore isolated nodes.

## Suggested Questions
_Questions this graph is uniquely positioned to answer:_

- **Why does `XtendM3 Capabilities Documentation` connect `XtendM3 Core APIs` to `Session & Batch Services`?**
  _High betweenness centrality (0.032) - this node is a cross-community bridge._
- **Why does `API Specification Overview` connect `XtendM3 Core APIs` to `Database APIs`?**
  _High betweenness centrality (0.024) - this node is a cross-community bridge._
- **Why does `_requested` connect `Package Metadata` to `Build & Project Config`?**
  _High betweenness centrality (0.016) - this node is a cross-community bridge._
- **Are the 19 inferred relationships involving `XtendM3 Project` (e.g. with `XtendM3 Development Process` and `XtendM3 Activation Process`) actually correct?**
  _`XtendM3 Project` has 19 INFERRED edges - model-reasoned connections that need verification._
- **Are the 15 inferred relationships involving `XtendM3 Capabilities Documentation` (e.g. with `ION API` and `MICaller API`) actually correct?**
  _`XtendM3 Capabilities Documentation` has 15 INFERRED edges - model-reasoned connections that need verification._
- **Are the 11 inferred relationships involving `API Specification Overview` (e.g. with `DatabaseAPI` and `ION API`) actually correct?**
  _`API Specification Overview` has 11 INFERRED edges - model-reasoned connections that need verification._
- **Are the 7 inferred relationships involving `Programming Standards` (e.g. with `Batch Extension` and `Table Extension (Dynamic Table)`) actually correct?**
  _`Programming Standards` has 7 INFERRED edges - model-reasoned connections that need verification._