# 📦 Deliverables

You asked for **both** a GitHub README portfolio **and** a GitHub Pages website in **two styles** (Minimalist HTML/CSS + React + Tailwind). Everything you need is below.

---

## 1) `README.md` (for your GitHub repo homepage)

> Create a new repo (or your profile repo), add this file as `README.md`.

```markdown
# NWABUEBO CHRISTOPHER EMMANUEL 

**Cybersecurity Enthusiast | Entry-Level Penetration Tester | Marine Engineer**

📧 **Email:** christopheremmanuel949@gmail.com  
📞 **Phone:** 07046431141 | 08073391941

---

## 🛡️ Skills & Tools

- ![Python](https://img.icons8.com/color/48/python--v1.png) **Python**
- ![SQL](https://img.icons8.com/ios-filled/50/sql.png) **SQL**
- ![Linux](https://img.icons8.com/color/48/linux--v1.png) **Linux**
- ![Nmap](https://img.icons8.com/ios-filled/50/network.png) **Nmap**
- ![John the Ripper](https://img.icons8.com/ios-glyphs/50/password.png) **John the Ripper**
- ![Burp Suite](https://img.icons8.com/ios-filled/50/bug.png) **Burp Suite**

> Tip: Add screenshots or badges for each tool in a `/assets/` folder to make this section visual.

---

## 🎓 Education
**National Diploma (ND)** – Marine Engineering

---

## 📜 Certifications
- ** Google Cybersecurity Certificate,
 IBM Cybersecurity Analyst,
 CompTIA Security+ prep)*

> Add certificate PDFs or links in a `certificates/` folder when you get them.

---

## 📈 Projects
- **Penetration Testing Labs** – Hands-on labs using **Nmap**, **John the Ripper**, **Burp Suite**.
- **Python Security Scripts** – Small tools for automation & scanning.
- **SQL Injection Test Cases** – Write-ups from safe lab environments.

---

## 🌐 Connect
- **GitHub:** https://github.com/YOUR_GITHUB_USERNAME
- **LinkedIn:** https://www.linkedin.com/in/christopher-nwabuebo-86bb36265
- **Twitter (X):** https://x.com/Carisyl9

---

### ⚡ *Passionate about Cybersecurity, Penetration Testing, and Network Defense*
```

> Replace `YOUR_GITHUB_USERNAME` with your real GitHub username.

---

## 2) Minimalist **GitHub Pages** site (HTML/CSS)

**Folder structure**

```
minimal-site/
├── index.html
└── styles.css
```

### `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Nwabuebo Christopher Emmanuel – Cybersecurity Portfolio</title>
  <link rel="stylesheet" href="styles.css" />
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
</head>
<body>
  <header class="container">
    <h1>Nwabuebo Christopher Emmanuel</h1>
    <p class="tag">Cybersecurity Enthusiast • Entry-Level Penetration Tester • Marine Engineer</p>
    <div class="contacts">
      <a href="mailto:christopheremmanuel949@gmail.com">christopheremmanuel949@gmail.com</a>
      <span>·</span>
      <a href="tel:+2347046431141">07046431141</a>
      <span>·</span>
      <a href="tel:+2348073391941">08073391941</a>
    </div>
    <nav class="links">
      <a href="https://github.com/YOUR_GITHUB_USERNAME" target="_blank" rel="noreferrer">GitHub</a>
      <a href="https://www.linkedin.com/in/christopher-nwabuebo-86bb36265" target="_blank" rel="noreferrer">LinkedIn</a>
      <a href="https://x.com/Carisyl9" target="_blank" rel="noreferrer">Twitter (X)</a>
    </nav>
  </header>

  <main class="container">
    <section>
      <h2>Skills & Tools</h2>
      <ul class="skills">
        <li><img src="https://img.icons8.com/color/48/python--v1.png" alt="Python icon"/> Python</li>
        <li><img src="https://img.icons8.com/ios-filled/50/sql.png" alt="SQL icon"/> SQL</li>
        <li><img src="https://img.icons8.com/color/48/linux--v1.png" alt="Linux icon"/> Linux</li>
        <li><img src="https://img.icons8.com/ios-filled/50/network.png" alt="Network/Nmap icon"/> Nmap</li>
        <li><img src="https://img.icons8.com/ios-glyphs/50/password.png" alt="Password/John the Ripper icon"/> John the Ripper</li>
        <li><img src="https://img.icons8.com/ios-filled/50/bug.png" alt="Bug/Burp Suite icon"/> Burp Suite</li>
      </ul>
    </section>

    <section>
      <h2>Education</h2>
      <p><strong>National Diploma (ND)</strong> – Marine Engineering</p>
    </section>

    <section>
      <h2>Certifications</h2>
      <ul>
        <li>Entry-Level Cybersecurity Certificate (e.g., Google Cybersecurity, IBM Cybersecurity Analyst, CompTIA Security+ prep)</li>
      </ul>
    </section>

    <section>
      <h2>Projects</h2>
      <article class="card">
        <h3>Penetration Testing Labs</h3>
        <p>Hands-on practice with <strong>Nmap</strong>, <strong>John the Ripper</strong>, and <strong>Burp Suite</strong>. Document findings and remediation steps.</p>
      </article>
      <article class="card">
        <h3>Python Security Scripts</h3>
        <p>Automation tools for scanning, recon, and reporting.</p>
      </article>
      <article class="card">
        <h3>SQL Injection Test Cases</h3>
        <p>Write-ups from safe, local lab environments exploring SQLi detection and prevention.</p>
      </article>
    </section>
  </main>

  <footer class="container foot">
    <small>© <span id="year"></span> Nwabuebo Christopher Emmanuel. All rights reserved.</small>
  </footer>

  <script>
    document.getElementById('year').textContent = new Date().getFullYear();
  </script>
</body>
</html>
```

### `styles.css`

```css
:root {
  --bg: #0b0f14;
  --fg: #e8eef6;
  --muted: #9fb3c8;
  --card: #121823;
  --accent: #3b82f6;
}
* { box-sizing: border-box; }
body { margin: 0; font-family: 'Inter', system-ui, -apple-system, Segoe UI, Roboto, Arial; color: var(--fg); background: radial-gradient(1200px 600px at 20% -10%, #18202e, #0b0f14); }
.container { max-width: 980px; margin: 0 auto; padding: 24px; }
h1 { font-size: 40px; margin: 0 0 8px; font-weight: 800; letter-spacing: 0.2px; }
.tag { color: var(--muted); margin: 0 0 16px; }
.contacts { color: var(--muted); display: flex; gap: 8px; flex-wrap: wrap; }
.contacts a { color: var(--fg); text-decoration: none; border-bottom: 1px dashed rgba(255,255,255,0.25); }
.links { margin-top: 12px; display: flex; gap: 14px; }
.links a { color: var(--fg); text-decoration: none; padding: 6px 10px; border: 1px solid rgba(255,255,255,0.15); border-radius: 999px; }

h2 { margin: 28px 0 12px; font-size: 24px; }
.skills { list-style: none; padding: 0; display: grid; grid-template-columns: repeat(auto-fill, minmax(220px, 1fr)); gap: 12px; }
.skills li { display: flex; align-items: center; gap: 10px; background: var(--card); padding: 12px 14px; border-radius: 16px; box-shadow: 0 1px 0 rgba(255,255,255,0.05) inset, 0 4px 16px rgba(0,0,0,0.35); }
.skills img { width: 28px; height: 28px; }

.card { background: var(--card); padding: 16px 18px; border-radius: 16px; box-shadow: 0 4px 16px rgba(0,0,0,0.35); margin-bottom: 12px; }
.foot { color: var(--muted); text-align: center; }
```

### Deploy (Minimalist site)

1. Create a new repo, e.g., `portfolio-minimal`.
2. Add both files (`index.html`, `styles.css`) to the repo root.
3. Commit & push.
4. In **Settings → Pages**, choose the `main` branch and `/root` for Pages. Your site will be live at: `https://YOUR_GITHUB_USERNAME.github.io/portfolio-minimal/`.

---

## 3) **React + Tailwind** (CDN, no build step)

This version uses React + Tailwind via CDNs (works perfectly on GitHub Pages—no tooling required).

**Folder structure**

```
react-tailwind-site/
└── index.html
```

### `index.html`

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8" />
  <meta name="viewport" content="width=device-width, initial-scale=1" />
  <title>Christopher Emmanuel – Cybersecurity Portfolio</title>
  <!-- Tailwind (Play CDN) -->
  <script src="https://cdn.tailwindcss.com"></script>
  <!-- React & ReactDOM -->
  <script crossorigin src="https://unpkg.com/react@18/umd/react.development.js"></script>
  <script crossorigin src="https://unpkg.com/react-dom@18/umd/react-dom.development.js"></script>
  <!-- Babel for JSX in the browser -->
  <script src="https://unpkg.com/@babel/standalone/babel.min.js"></script>
  <link rel="preconnect" href="https://fonts.googleapis.com">
  <link rel="preconnect" href="https://fonts.gstatic.com" crossorigin>
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@400;600;800&display=swap" rel="stylesheet">
  <style>
    body { font-family: 'Inter', system-ui, -apple-system, Segoe UI, Roboto, Arial; }
  </style>
</head>
<body class="bg-slate-950 text-slate-100">
  <div id="root"></div>

  <script type="text/babel">
    const skills = [
      { name: 'Python', img: 'https://img.icons8.com/color/48/python--v1.png' },
      { name: 'SQL', img: 'https://img.icons8.com/ios-filled/50/sql.png' },
      { name: 'Linux', img: 'https://img.icons8.com/color/48/linux--v1.png' },
      { name: 'Nmap', img: 'https://img.icons8.com/ios-filled/50/network.png' },
      { name: 'John the Ripper', img: 'https://img.icons8.com/ios-glyphs/50/password.png' },
      { name: 'Burp Suite', img: 'https://img.icons8.com/ios-filled/50/bug.png' },
    ];

    function Badge({ href, children }) {
      return (
        <a href={href} target="_blank" rel="noreferrer" className="inline-flex items-center gap-2 rounded-full border border-white/15 px-3 py-1 hover:border-white/30 transition">
          {children}
        </a>
      );
    }

    function Card({ title, children }) {
      return (
        <section className="rounded-2xl bg-slate-900/60 shadow-xl ring-1 ring-white/10 p-6">
          <h3 className="text-lg font-semibold mb-2">{title}</h3>
          <div className="text-slate-300">{children}</div>
        </section>
      );
    }

    function App() {
      return (
        <div className="min-h-screen">
          <header className="max-w-5xl mx-auto px-6 pt-10 pb-6">
            <h1 className="text-4xl md:text-5xl font-extrabold">Nwabuebo Christopher Emmanuel</h1>
            <p className="text-slate-300 mt-2">Cybersecurity Enthusiast • Entry-Level Penetration Tester • Marine Engineer</p>
            <div className="flex flex-wrap items-center gap-2 text-slate-300 mt-3">
              <a href="mailto:christopheremmanuel949@gmail.com" className="underline underline-offset-4">christopheremmanuel949@gmail.com</a>
              <span>·</span>
              <a href="tel:+2347046431141" className="underline underline-offset-4">07046431141</a>
              <span>·</span>
              <a href="tel:+2348073391941" className="underline underline-offset-4">08073391941</a>
            </div>
            <div className="flex gap-3 mt-4">
              <Badge href="https://github.com/YOUR_GITHUB_USERNAME">GitHub</Badge>
              <Badge href="https://www.linkedin.com/in/christopher-nwabuebo-86bb36265">LinkedIn</Badge>
              <Badge href="https://x.com/Carisyl9">Twitter (X)</Badge>
            </div>
          </header>

          <main className="max-w-5xl mx-auto px-6 space-y-6 pb-16">
            <section>
              <h2 className="text-2xl font-bold mb-3">Skills & Tools</h2>
              <ul className="grid grid-cols-1 sm:grid-cols-2 md:grid-cols-3 gap-3">
                {skills.map((s) => (
                  <li key={s.name} className="flex items-center gap-3 rounded-2xl bg-slate-900/60 ring-1 ring-white/10 p-4">
                    <img src={s.img} alt={`${s.name} icon`} className="w-8 h-8" />
                    <span className="font-medium">{s.name}</span>
                  </li>
                ))}
              </ul>
            </section>

            <Card title="Education">
              <p><strong>National Diploma (ND)</strong> – Marine Engineering</p>
            </Card>

            <Card title="Certifications">
              <ul className="list-disc list-inside">
                <li>Entry-Level Cybersecurity Certificate (e.g., Google Cybersecurity, IBM Cybersecurity Analyst, CompTIA Security+ prep)</li>
              </ul>
            </Card>

            <section className="space-y-3">
              <h2 className="text-2xl font-bold">Projects</h2>
              <Card title="Penetration Testing Labs">
                Hands-on practice with <strong>Nmap</strong>, <strong>John the Ripper</strong>, and <strong>Burp Suite</strong>. Document findings and remediation.
              </Card>
              <Card title="Python Security Scripts">
                Automation tools for scanning, recon, and reporting.
              </Card>
              <Card title="SQL Injection Test Cases">
                Write-ups from safe lab environments exploring SQLi detection and prevention.
              </Card>
            </section>
          </main>

          <footer className="max-w-5xl mx-auto px-6 pb-10 text-slate-400 text-sm">
            © {new Date().getFullYear()} Nwabuebo Christopher Emmanuel. All rights reserved.
          </footer>
        </div>
      );
    }

    const root = ReactDOM.createRoot(document.getElementById('root'));
    root.render(<App />);
  </script>
</body>
</html>
```

### Deploy (React + Tailwind CDN)

1. Create a new repo, e.g., `portfolio-react`.
2. Put the `index.html` above in the repo root.
3. Commit & push.
4. In **Settings → Pages**, choose `main` branch and `/root`. Your site will be live at: `https://YOUR_GITHUB_USERNAME.github.io/portfolio-react/`.

---

## Optional Enhancements

* Add a `projects/` folder with individual write-ups (Markdown or HTML).
* Add a `certificates/` folder and link to PDFs.
* Replace icons’ external URLs with local files in `/assets/` so they work offline.
* Add a contact form via Formspree or Netlify Forms (no backend needed).

---

## Where to put your username

* Replace every `YOUR_GITHUB_USERNAME` with your actual GitHub username (profile & links).

## Done ✅

If you want, I can also package these into a downloadable ZIP with folders laid out exactly as shown.
