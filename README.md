<div align="center">

  <!-- Header Banner -->
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,50:1e293b,100:38bdf8&height=220&section=header&text=Celestial%203D%20Profile%20Suite%20%F0%9F%AA%90&fontSize=42&fontColor=ffffff&fontAlignY=38&animation=fadeIn&desc=Turn%20Your%20GitHub%20Profile%20into%20a%20High-Tech%20Spatial%20Observatory&descSize=16&descAlignY=60" width="100%"/>

  <h1>🪐 Celestial &amp; 3D Spatial GitHub Profile Template</h1>
  <p><b>A modern, aesthetic, and interactive GitHub Profile suite with 3D keycaps, telemetry HUD, voxel grass &amp; automated GitHub Actions.</b></p>

  <p>
    <a href="https://github.com/strongsun806/celestial-github-profile/stargazers">
      <img src="https://img.shields.io/github/stars/strongsun806/celestial-github-profile?style=for-the-badge&logo=apachespark&color=fbbf24&logoColor=black" alt="GitHub Stars"/>
    </a>
    <a href="https://github.com/strongsun806/celestial-github-profile/network/members">
      <img src="https://img.shields.io/github/forks/strongsun806/celestial-github-profile?style=for-the-badge&logo=git&color=38bdf8&logoColor=white" alt="GitHub Forks"/>
    </a>
    <a href="https://github.com/strongsun806/celestial-github-profile/blob/main/LICENSE">
      <img src="https://img.shields.io/badge/License-MIT-34d399?style=for-the-badge" alt="License"/>
    </a>
  </p>

  <p>
    <b>⭐ If this template helps level up your profile, please leave a Star to support! ⭐</b>
  </p>

  <p>
    <a href="#-quick-start-60-seconds"><b>🚀 Quick Start</b></a> •
    <a href="#-whats-included"><b>📦 What's Included</b></a> •
    <a href="#-live-components-preview"><b>👀 Live Preview</b></a> •
    <a href="#-automation-workflows"><b>⚙️ Automation Actions</b></a> •
    <a href="#-customization-guide"><b>🎨 Customization</b></a>
  </p>

</div>

<br/>

---

<br/>

## 🚀 Quick Start (60 Seconds)

You can set up this high-tech profile in **3 simple steps**:

### 1️⃣ Click "Use this template"
Click the green **[Use this template]** button at the top right of this repository, or clone it.
> ⚠️ **Important**: Name your new repository exactly the same as your **GitHub Username** (e.g., `https://github.com/your-username/your-username`).

### 2️⃣ Copy & Fill the Template
1. Open [`template/README.template.md`](./template/README.template.md).
2. Copy its contents into your root `README.md`.
3. Replace the placeholders:
   - `{{YOUR_GITHUB_USERNAME}}` ➔ Your GitHub handle (e.g. `strongsun806`)
   - `{{YOUR_NAME}}` ➔ Your display name
   - `{{YOUR_ROLE}}` ➔ Your job title or tech specialization
   - `{{YOUR_EMAIL}}` ➔ Your contact email

### 3️⃣ Enable GitHub Actions (For 3D Grass & Summary Cards)
1. Go to your repo **Settings** > **Actions** > **General**.
2. Under **Workflow permissions**, select **"Read and write permissions"** and check **"Allow GitHub Actions to create and approve pull requests"**.
3. Go to the **Actions** tab and click **Run workflow** on:
   - `GitHub-Profile-3D-Contrib` (generates the 3D isometric contribution blocks)
   - `GitHub-Profile-Summary-Cards` (generates commit & language cards)
   - `Generate-Contribution-Snake` (generates the animated contribution snake)

🎉 **Done! Your GitHub profile is now transformed into a futuristic 3D observatory!**

<br/>

---

<br/>

## 📦 What's Included

| Component | Description | Preview File |
| :--- | :--- | :--- |
| **🪐 Celestial Geometry Emblem** | Rotating orbital rings with 3D octahedron crystal core | [`assets/celestial-geometry.svg`](./assets/celestial-geometry.svg) |
| **🧪 Visual R&D Lab HUD** | Animated 4D Hypercube, GLSL oscilloscope waveforms & radar | [`assets/visual-lab-hud.svg`](./assets/visual-lab-hud.svg) |
| **🎹 3D Tactile Keycaps** | Mechanical keycap styled interactive skillset deck | [`assets/3d-keycaps.svg`](./assets/3d-keycaps.svg) |
| **🧊 3D Milestone Cubes** | Floating isometric cards for featured projects | [`assets/3d-milestone-cubes.svg`](./assets/3d-milestone-cubes.svg) |
| **🌱 Automated 3D Grass** | GitHub Actions workflow generating nightly 3D voxels | [`.github/workflows/profile-3d-contrib.yml`](./.github/workflows/profile-3d-contrib.yml) |
| **📊 Summary Cards Action** | Multi-theme language & commit breakdown cards | [`.github/workflows/profile-summary-cards.yml`](./.github/workflows/profile-summary-cards.yml) |
| **🐍 Snake Grid Action** | Contribution-eating animated cyber snake | [`.github/workflows/snake-contrib.yml`](./.github/workflows/snake-contrib.yml) |

<br/>

---

<br/>

## 👀 Live Components Preview

### 1. 🪐 Celestial Geometry Emblem & Visual Lab HUD
Pure SVG with smooth native CSS animations. No broken links, no server downtime.

<div align="center">
  <img src="./assets/celestial-geometry.svg" width="160" alt="Celestial Geometry Emblem"/>
  <br/><br/>
  <img src="./assets/visual-lab-hud.svg" width="95%" alt="Visual Lab HUD Telemetry Console"/>
</div>

<br/>

### 2. 🎹 3D Tactile Skill Deck & Isometric Cubes
Eye-catching 3D perspective graphics designed specifically for GitHub Dark Mode.

<div align="center">
  <img src="./assets/3d-keycaps.svg" width="95%" alt="3D Tactile Keycaps"/>
  <br/><br/>
  <img src="./assets/3d-milestone-cubes.svg" width="95%" alt="3D Milestone Cubes"/>
</div>

<br/>

---

<br/>

## ⚙️ Automation Actions Setup

This repository contains pre-configured GitHub Actions that run automatically every night:

```yaml
# Runs automatically every day at 18:00 UTC
- uses: yoshi389111/github-profile-3d-contrib@latest
# Runs automatically every day at 19:00 UTC
- uses: vn7n24fzkq/github-profile-summary-cards@release
# Runs automatically every day at 20:00 UTC
- uses: Platane/snk/svg-only@v3
```

All output SVGs are automatically pushed directly to your repository, keeping your profile 100% up-to-date with zero manual maintenance!

<br/>

---

<br/>

## 🎨 Customization Tips

<details>
<summary><b>✨ How to edit the Typing SVG lines</b></summary>

In your `README.md`, find the `readme-typing-svg` link and change the URL parameters:
```markdown
https://readme-typing-svg.demolab.com?color=38BDF8&lines=Line+1;Line+2;Line+3
```
You can customize text, typing speed, and hex color codes.
</details>

<details>
<summary><b>🎨 How to adjust SVG colors</b></summary>

All SVGs in the `assets/` folder use clean, commented SVG code. Open any `.svg` file in your favorite editor to tweak:
- Core gradient stops (e.g. `#38bdf8`, `#818cf8`, `#fbbf24`)
- Stroke widths and rotation animation speeds
</details>

<br/>

---

<br/>

<div align="center">

  <h3>🌟 Liked this template?</h3>
  <p>Give this repository a <b>Star (⭐)</b> on GitHub and share it with your developer friends!</p>

  <br/>

  <a href="https://github.com/strongsun806/celestial-github-profile">
    <img src="https://img.shields.io/badge/⭐_Star_This_Repository-fbbf24?style=for-the-badge&logo=github&logoColor=black"/>
  </a>

  <br/><br/>

  <sub>Crafted with 💙 &amp; Spatial Web passion by <a href="https://github.com/strongsun806"><b>Hyegang Kwon (@strongsun806)</b></a></sub>

</div>
