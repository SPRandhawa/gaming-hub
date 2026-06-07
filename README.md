<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0d1117,50:0a3d62,100:00b4d8&height=220&section=header&text=🎮%20Gaming%20Hub&fontSize=50&fontColor=00f5ff&fontAlignY=40&desc=All-in-One%20Web%20Gaming%20Platform%20%7C%201-Day%20MVP%20Sprint&descAlignY=60&descColor=a0e9ff&animation=fadeIn" alt="Header Banner" width="100%"/>
</div>

<br/>

<div align="center">
  <img src="https://img.shields.io/badge/Status-Stable-2ecc71?style=flat-square" alt="Status" />
  <img src="https://img.shields.io/badge/Environment-Frontend-00b4d8?style=flat-square" alt="Environment" />
  <img src="https://img.shields.io/badge/Built%20In-1%20Day-ff6b6b?style=flat-square" alt="Sprint Duration" />
  <img src="https://img.shields.io/badge/Architecture-Modular%20SPA-6e40c9?style=flat-square" alt="Architecture" />
</div>

<br/>

---

<h2>🎯 Project Overview</h2>
<p>
<b>Gaming Hub</b> is a centralized, lightweight, single-page application (SPA) dashboard containing multiple classic video games. Built as an intense 24-hour MVP engineering sprint, the platform serves as an efficient digital lounge separating localized multi-player single-screen games from procedural computer-driven algorithmic logic.
</p>

<br/>

---

<h2>🎛️ Platform Architecture</h2>
<p>
The core gaming engine layout splits all integrated modules into two major behavioral categories based on environmental input processing constraints:
</p>

<div align="center">
  <table>
    <tr>
      <td align="center" width="50%">
        <h3>🤖 With Computer (vs. AI)</h3>
        <p><i>Processes heuristic array patterns and script-driven decisions.</i></p>
        <hr/>
        <ul style="text-align: left;">
          <li><b>Tic-Tac-Toe (AI Mode):</b> Condition-based defensive matrix blocking.</li>
          <li><b>Word Search:</b> Matrix pattern matching.</li>
          <li><b>Chess:</b> Engine-calculated move validations.</li>
        </ul>
      </td>
      <td align="center" width="50%">
        <h3>👥 Without Computer (Solo / Pass & Play)</h3>
        <p><i>State management optimized for local multiplayer or canvas rendering.</i></p>
        <hr/>
        <ul style="text-align: left;">
          <li><b>Snake & Ladder:</b> Index offset manipulation via dice generation.</li>
          <li><b>Running Game:</b> Coordinate updates with pseudo-gravity loops.</li>
          <li><b>Fruit Cut:</b> Real-time vector swipe-intersection engine.</li>
        </ul>
      </td>
    </tr>
  </table>
</div>

<br/>

---

<h2>⚡ Technical Highlights & Optimization</h2>

* **Zero-Lag Asset Recycling (Object Pooling):** Designed the physics-based *Running Game* mechanics using dynamic object queues to recycle active boundary segments, completely eliminating browser garbage-collection stutter.
* **State Matrix Computations:** Implemented mathematical grid layouts for *Tic-Tac-Toe* and *Snake & Ladder* utilizing explicit coordinate mapping algorithms rather than raw DOM elements:
    $$\text{Target Position} = \text{Current Index} + \Delta\text{Modifier}$$
* **Decoupled Architecture:** Built using independent encapsulated JavaScript runtime states. Every single sub-game maintains its own standalone execution scope, which allows the main hub shell to swap components smoothly without cross-contamination.

<br/>

---

<h2>🛠️ Technology Stack</h2>

* **Core UI Layout:** HTML5, CSS3, Tailwind CSS (Modern Dark Cyber Palette)
* **Game Engine Runtime:** Vanilla JavaScript (ES6 Modules)
* **Graphics Pipeline:** HTML5 Canvas API (for real-time coordinate plotting in *Fruit Cut* and *Running Game*)
* **Hosting Optimization:** Vercel Continuous Deployment

<br/>

---
