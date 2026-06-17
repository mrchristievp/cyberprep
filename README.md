# AP Cybersecurity — Units 4 & 5 Study Suite

An interactive, single-file study app for AP Cybersecurity Units 4 (Securing Devices)
and 5 (Securing Applications and Data). No build step, no dependencies, no internet
required — everything is contained in `index.html`.

## Study modes

| Mode | What it does |
|------|--------------|
| **Flashcards** | Flip 55 key terms between term and definition; shuffle and step through. |
| **Quiz** | Multiple-choice term → definition with running score and a results screen. |
| **Match** | Pair up to 8 terms with their definitions; wrong pairs flash red. |
| **Order steps** | Parsons problems — drag-free click-to-place ordering of attack/defense processes (password hashing, rainbow table, SQL injection, signature detection). |
| **Log lab** | Analyze realistic authentication logs to spot brute force, password spraying, credential stuffing, and anomalous logins. |
| **Scenarios** | Applied questions (risk assessment, malware ID, access control, XSS, chmod) with progressive hints and full explanations. |

The harder modes (Order steps, Log lab, Scenarios) include **progressive hints** —
reveal one clue at a time — and a written **explanation** after you answer.

## Filtering

Flashcards, Quiz, and Match can be filtered by **CompTIA Security+ (SY0-701) domain**:

- **Domain 1 — General security concepts** (cryptography, least privilege)
- **Domain 2 — Threats, vulnerabilities & mitigations** (malware, password & application attacks)
- **Domain 3 — Security architecture** (data states, data classification, host firewall)
- **Domain 4 — Security operations** (detection/monitoring, authentication, access control models)

## Running it

Open `index.html` in any modern browser. That's it.

## Deploying to GitHub Pages

1. Create a new repository and upload the contents of this folder (`index.html` + `README.md`).
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to *Deploy from a branch*, pick your
   default branch and the `/ (root)` folder, and save.
4. After a minute, your site is live at `https://<your-username>.github.io/<repo-name>/`.

Because the file is named `index.html`, GitHub Pages serves it automatically at the root URL.

## Content source

Definitions and scenarios are drawn from the College Board AP Cybersecurity Course
Framework (Units 4 & 5 essential knowledge statements).
