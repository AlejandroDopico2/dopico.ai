# dopico.ai — Research Link Hub

This repository hosts the **centralized short-link system** for [dopico.ai](https://dopico.ai.github.io).  
It provides simple, persistent paths (e.g. `dopico.ai/cifnet`) that automatically **redirect to the latest full URLs** for my research projects, papers, benchmarks, and other academic resources.

---

## 🔍 How It Works
- All redirects are defined in a local [`links.json`](./links.json) file.  
- When a user visits a short path (e.g. `/paper`), the script checks if it exists in the list and instantly redirects to the corresponding destination URL.  
- If no redirect is triggered, the page displays a **clean index of all research links** with their descriptions.

---

## Motivation
Academic links often change, i.e, project pages move, papers get new DOIs, or demos migrate.  
This lightweight hub ensures that shared short links **remain stable and up to date**, serving as a long-term entry point to my research.

---

## 🚀 Deployment
This page is designed to be hosted on **GitHub Pages**.  
Simply push updates to `links.json` to add or update redirects instantly.

---

**© 2025 Alejandro Dopico-Castro**  
[https://dopico.ai.github.io](https://dopico.ai.github.io)
