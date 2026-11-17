<p align="center">
  <a href="https://mkaczmarczyk.com"><img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/banner.svg" alt="Maciej Kaczmarczyk, full-stack developer" width="100%"></a>
</p>

<p align="center">
  <a href="https://mkaczmarczyk.com/en/"><img src="https://img.shields.io/badge/Portfolio-mkaczmarczyk.com-ff7844?style=for-the-badge&labelColor=111211" alt="Portfolio"></a>
  <a href="https://apps.shopify.com/partners/lektor"><img src="https://img.shields.io/badge/Shopify_App_Store-9_apps-7AB55C?style=for-the-badge&logo=shopify&logoColor=white&labelColor=111211" alt="Shopify apps"></a>
  <a href="https://www.roblox.com/games/116481735425004/Parcel-Empire-Tycoon"><img src="https://img.shields.io/badge/Play_on_Roblox-Parcel_Empire_Tycoon-ff7844?style=for-the-badge&logo=roblox&logoColor=white&labelColor=111211" alt="Parcel Empire Tycoon on Roblox"></a>
  <img src="https://img.shields.io/badge/Open_to-remote_work_%26_projects-2ea043?style=for-the-badge&labelColor=111211" alt="Open to work">
</p>

I build production systems for businesses: ordering portals, integrations with ERP, couriers and e-invoicing, and automations that use AI where it actually saves time. I talk to the people who will use the system, turn what they need into a plan, ship a first version fast and keep improving it with them.

<p align="center"><img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/numbers.svg" alt="388 podcast episodes transcribed, 3.0M words, 9 Shopify apps, 3 Roblox games, ~20 Minecraft modules" width="100%"></p>

## Selected work

<table>
<tr>
<td colspan="2" valign="top">
<a href="https://github.com/LektorGW/mtc-tactical-assistant"><img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/mtc-map-panel.png" alt="MTC Tactical Assistant main panel" width="100%"></a>
<h3>MTC Tactical Assistant · <a href="https://github.com/LektorGW/mtc-tactical-assistant">source on GitHub</a></h3>
<sub>Rust · Tauri 2 · React 19 · TypeScript · local OCR · 109 UI tests</sub>
<p>A Windows desktop app that reads a game's map and HUD from the screen with local OCR and turns it into a firing solution in a transparent overlay. Ballistics solver with drag and rocket-motor models (RK4), 3D intercept for moving targets, map calibration from two points, 153 projectile profiles for 51 weapons. Core logic is a workspace of 6 Rust crates behind a React UI.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/mitopharma.png" alt="B2B wholesale ordering portal">
<h3>B2B wholesale ordering portal</h3>
<sub><b>In production</b> · Next.js 15 · React 19 · TypeScript · Prisma · C#/.NET</sub>
<p>Customer-specific prices, quick ordering by product code, invoices and balances. My C#/.NET connector syncs orders both ways with the Subiekt GT ERP, shipments go through DHL, InPost and Orlen Paczka APIs, and the sales team gets an AI assistant that only sees pseudonymised data. First working version in a week.</p>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/rtr-archiwum.png" alt="Searchable podcast archive">
<h3>Searchable podcast archive</h3>
<sub><b>Client in the US</b> · Python · Whisper · FFmpeg</sub>
<p>388 episodes and 355 hours of audio turned into 3 million searchable words. Every episode summarized and tagged, and search jumps straight to the moment in the audio. Built with a parallel transcription pipeline that survives interruptions.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/lektoro-customs.png" alt="Lektoro Shopify apps">
<h3>Lektoro · 9 Shopify apps</h3>
<sub><a href="https://apps.shopify.com/partners/lektor">Shopify App Store</a> · TypeScript · React Router</sub>
<p>EU product compliance (GPSR, EPR), HS codes and customs data, stock and sync monitoring, purchase orders with MOQ, price rounding.</p>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/panorama-plan.png" alt="Shopping centre interactive floor plan">
<h3>Shopping centre website</h3>
<sub><a href="https://chpanorama.pl">chpanorama.pl</a> · Laravel 11 · Filament · Alpine.js</sub>
<p>Interactive floor plan connected to the store directory: level switching, search, zoom and a unit card drawn on the architectural plans. Tenants, promotions and events managed in a Filament CMS.</p>
</td>
</tr>
<tr>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/osiedle-wybor.png" alt="Interactive apartment selector">
<h3>Housing development website</h3>
<sub><a href="https://osiedlepodksiazem.pl/">osiedlepodksiazem.pl</a> · React · Vite · Tailwind CSS</sub>
<p>Interactive selector drawn on the architectural renders: pick a building, hover a floor to see how many apartments are still available, then open the exact floor plan of a single apartment.</p>
</td>
<td width="50%" valign="top">
<img src="https://raw.githubusercontent.com/LektorGW/LektorGW/main/assets/electio.jpg" alt="Electio foundation website">
<h3>Foundation website &amp; CMS</h3>
<sub><a href="https://electio.org.pl">electio.org.pl</a> · Laravel 12 · Livewire 3 · Filament</sub>
<p>Migrated from WordPress to a custom Laravel app with an admin panel: district map, projects and events, online donations through PayU, newsletter with double opt-in, cookie-free analytics and technical SEO.</p>
</td>
</tr>
</table>

<details>
<summary><b>More projects</b></summary>
<br>

- **Bakery operations system** · Next.js 16, Drizzle, KSeF, Dotykačka POS. Raw material stock, recipes with costing, production orders, transfers between shops, national e-invoicing. Built in 4 days part-time with AI coding agents.
- **Roblox** · 3 published games: [Parcel Empire Tycoon](https://www.roblox.com/games/116481735425004/Parcel-Empire-Tycoon) (main project), [Space Garden](https://www.roblox.com/games/101257030687266/Space-Garden) (190+ automated tests) and Rush to the Storm Egg!.
- **Hackathons** · [tender-lens](https://github.com/LektorGW/tender-lens) (on-device + Firebase AI tender analysis) · [mistakemap](https://github.com/LektorGW/mistakemap) (misconception maps for teachers).

</details>

## Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,nodejs,tailwind,vite,prisma,php,laravel,python,flask,fastapi,cs,dotnet,java,rust,tauri&perline=17" alt="Languages and frameworks"><br>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,docker,linux,bash,cloudflare,git,github,wordpress&perline=11" alt="Tools and platforms">
</p>

## How I work with AI

I use AI coding agents (Claude Code, Codex) every day. I write the spec and acceptance criteria, the agent drafts the change, and I review the diff and test it before anything ships. Business logic, client data and security I check myself: the agent writes faster, but the code is my responsibility.

<p align="center">
  <sub>Linux Essentials · Cisco Networking Academy · <a href="https://mkaczmarczyk.com">mkaczmarczyk.com</a></sub>
</p>
