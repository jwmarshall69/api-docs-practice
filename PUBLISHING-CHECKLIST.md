# ✅ Publishing Checklist – API Docs Practice + Portfolio

## 1. Prepare Locally

- [ ] Unzip `api-docs-practice-complete-portfolio.zip` (practice repo).
- [ ] Unzip `api-writer-portfolio.zip` (portfolio site).
- [ ] Open each in **VS Code** to confirm file structure and README badges look correct.

---

## 2. Push the Practice Repo

- [ ] Create a new repo on GitHub: `api-docs-practice`.
- [ ] In **GitHub Desktop** (or CLI):

  ```bash
  git init
  git add .
  git commit -m "Initial commit: API Docs Practice"
  git branch -M main
  git remote add origin https://github.com/your-username/api-docs-practice.git
  git push -u origin main
  ```

- [ ] Confirm files appear on GitHub (`README.md`, `guides/`, `api/`, `.github/`).

---

## 3. Enable GitHub Pages for Practice Repo

- [ ] Go to **Settings → Pages**.
- [ ] Source → **Deploy from a branch**.
- [ ] Branch: `main`, Folder: `/root`.
- [ ] Save → wait for green check → test site at:  
      `https://github.com/jwmarshall69/api-docs-practice`.

---

## 4. Push the Portfolio Site

- [ ] Create a new repo: `api-writer-portfolio`.
- [ ] Push files the same way as Step 2.
- [ ] Update placeholders:
  - `_config.yml` → replace `your-username` and update `description`.
  - `_data/projects.yml` → add real repo URLs (start with `api-docs-practice`).
  - `contact.md` → update GitHub, LinkedIn, Email links.

---

## 5. Enable GitHub Pages for Portfolio

- [ ] Go to **Settings → Pages**.
- [ ] Source → **Deploy from a branch**.
- [ ] Branch: `main`, Folder: `/root`.
- [ ] Save → test site at:  
      `https://github.com/jwmarshall69/api-writer-portfolio/`.

---

## 6. Test & Polish

- [ ] Open both sites in a browser.
- [ ] Click links in nav + project cards → ensure they resolve.
- [ ] Check **badges in README** update with CI status after first PR.
- [ ] Verify spelling/links workflows run under the **Actions** tab.

---

## 7. Share Your Work

- [ ] Add portfolio link to LinkedIn & resume.
- [ ] Keep `_data/projects.yml` updated as you add more repos.
- [ ] Use Issues + PR templates to practice real-world contribution flow.

---

👉 By the end, you’ll have:

- A **Practice Repo** with working CI, Pages, and docs templates.  
- A **Portfolio Site** showcasing all your writing projects in one clean GitHub Pages

