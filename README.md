<p align="center">
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/react/react-original.svg" alt="React" width="50" height="50" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/typescript/typescript-original.svg" alt="TypeScript" width="50" height="50" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/vitejs/vitejs-original.svg" alt="Vite" width="50" height="50" />
  &nbsp;&nbsp;&nbsp;&nbsp;
  <img src="https://raw.githubusercontent.com/devicons/devicon/master/icons/supabase/supabase-original.svg" alt="Supabase" width="50" height="50" />
</p>

<h1 align="center">Portal-Hub</h1>

<p align="center">
  A centralized, personal resource management dashboard designed for storing, organizing, and quickly accessing web links, documents, memos, and quick notes.
</p>

<p align="center">
  <a href="https://baralaayush.github.io/Portal-Hub/"><strong>🌐 Live Demo</strong></a>
</p>

---

## ✨ Key Features

* **Link & Resource Organizer:** Categorize and save essential web URLs, documents, and reference materials in one place.
* **Memos & Notes:** Create, edit, and keep track of daily memos and text snippets.
* **Cloud Persistence:** Seamless backend storage and database synchronization powered by Supabase.
* **Automated Workflows:** Includes a GitHub Actions keep-alive workflow (`supabase-keepalive.yml`) to keep free-tier Supabase instances active.
* **Modern UI:** Responsive layout built with React and TypeScript for fast navigation.

---

## 🛠️ Tech Stack & Dependencies

* **Frontend Framework:** React (`react`, `react-dom`)
* **Language:** TypeScript
* **Database & BaaS:** Supabase (`@supabase/supabase-js`)
* **Build Tooling & Bundler:** Vite (`vite`, `@vitejs/plugin-react`)

---

## 📁 Repository Structure

```text
.
├── .github/workflows/   # CI/CD workflows (Supabase keep-alive schedule)
├── components/          # Reusable UI components (modals, resource cards, inputs)
├── App.tsx              # Main application component & layout state
├── index.html           # HTML entry point
├── index.tsx            # React application root mount
├── supabaseClient.ts    # Supabase client instance configuration
├── tsconfig.json        # TypeScript compiler configuration
├── vite.config.ts       # Vite bundler configuration
└── package.json         # Project metadata, dependencies, and build scripts
