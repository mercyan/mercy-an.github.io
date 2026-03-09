# mengqi-an.me — Personal Website

Personal academic website for Mengqi "Mercy" An, Visiting Assistant Professor of Asian Studies at Colorado College.

---

## How to Publish on GitHub Pages

### Step 1 — Create a GitHub repository

1. Go to [github.com](https://github.com) and sign in (or create a free account).
2. Click the **+** icon in the top-right → **New repository**.
3. Name it exactly: `mengqi-an.github.io`
   *(Replace `mengqi-an` with your actual GitHub username if different.)*
4. Set it to **Public**.
5. Click **Create repository**.

### Step 2 — Upload your files

1. On the new repository page, click **uploading an existing file**.
2. Drag and drop **all files** from this folder:
   - `index.html`
   - `README.md`
   - All PDF files
3. Click **Commit changes**.

### Step 3 — Enable GitHub Pages

1. Go to your repository **Settings** → **Pages** (in the left sidebar).
2. Under "Source", select **Deploy from a branch**.
3. Choose branch: **main**, folder: **/ (root)**.
4. Click **Save**.

GitHub will show you a URL like `https://mengqi-an.github.io` — your site will be live within a minute or two.

### Step 4 — Connect your custom domain (mengqi-an.me)

1. Still in **Settings → Pages**, find the "Custom domain" field.
2. Type `mengqi-an.me` and click **Save**.
3. GitHub will create a `CNAME` file automatically.

Then, in your domain registrar (wherever you bought `mengqi-an.me`):

4. Add a **CNAME record**:
   - Name / Host: `www`
   - Value / Target: `mengqi-an.github.io`
5. Add **four A records** (for the apex/root domain):
   - Name / Host: `@`
   - Values (add one record for each):
     ```
     185.199.108.153
     185.199.109.153
     185.199.110.153
     185.199.111.153
     ```

DNS changes can take up to 24 hours to propagate. After that, `https://mengqi-an.me` will serve your new site.

---

## Updating the Site

To update content, simply edit `index.html` in GitHub (click the file → pencil icon) and commit.
To add new documents, upload new PDF files to the repository.

## File Structure

```
/
├── index.html                          ← Main website
├── README.md                           ← This file
├── PA111 Introduction to Asian Studies.pdf
├── Syllabus_2025_Block5_An.pdf
├── Syllabus_2025_Block6_An.pdf
├── Writing Workshop.pdf
├── Teaching Support doc.pdf
└── An_Evidence of Teaching Effectiveness.pdf
```
