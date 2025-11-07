# Logistics & Transportation – Specialized Knapsack Optimizer

A dynamic, interactive browser-based tool built using **HTML**, **CSS**, and **JavaScript**, designed to optimize cargo load planning for logistics operations by applying the Knapsack algorithm under weight and volume constraints.

## 🎯 Project Overview

- **Title:** Logistics & Transportation – Specialized Knapsack Optimizer  
- **Developed by:**  
    
  - Md Fuzail (23TEC2CS567) ★ (Project Leader)  

- **Year & Section:** 3rd Year, Section E  
- **Institution:** Vivekananda Global University (VGU), CSE Department

## 🧠 Synopsis
This project addresses the real-world logistics challenge of efficiently loading items onto a vehicle or ship. The tool computes the optimal set of items to maximize total value while respecting a vehicle’s weight (and optionally volume) capacity by applying the Knapsack algorithm.

## 🎯 Objective
To create an intuitive, browser-based solution that supports logistics planners in determining optimal load configurations—enhancing transport efficiency, reducing costs, and improving resource utilization—using accessible web technologies.

## 🛠️ Key Features
- Two solver modes:  
  - **Weight-only** (exact 0/1 Knapsack via dynamic programming)  
  - **Weight + Volume** (exact Pareto-front DP, with fallback to approximate greedy local search if needed)  
- Interactive item list (add/remove/edit items: name, weight, volume, value)  
- Import/export capabilities:  
  - **CSV** for items (load or download list)  
  - **JSON scenario export** (save and reload full configuration: items + capacities + mode)  
- Live results with:  
  - Real-time selected items list  
  - Highlight of selected items in the table  
  - Expandable legend/tooltip explaining "Mode", "Weight (W)", "Volume (V)", "Max Value"  
- Fixed top header UI for easy access to controls  
- Single-file implementation (no frameworks) for easy deployment  
- Light-mode only design, fully responsive for desktop & mobile

## 🧩 How to Use
1. Open `index.html` in your browser.  
2. Select solver **Mode** (Weight-only or Weight + Volume).  
3. Set capacities:  
   - Weight capacity (required)  
   - Volume capacity (used when Mode = Weight + Volume)  
4. Manage item list: edit existing items or add new ones (name, weight, volume, value).  
5. Click **Solve** to compute the optimal load.  
6. View selected items, max value, and highlight within table.  
7. Expand the Legend box (ⓘ) to understand each parameter’s meaning.  
8. Use top header buttons to:  
   - Export current view as PDF/print  
   - Import items via CSV  
   - Export items via CSV  
   - Save or load a scenario via JSON  
   - Toggle project details section if needed  

## 📝 Software & Hardware Requirements
- **Software:** Any modern browser (Chrome, Firefox, Edge, Safari)  
- **Hardware:** Standard PC or laptop – e.g., Intel i3 / 4 GB RAM or higher; Internet only required if loading external resources  
- Single file, no installation required—ideal for quick deployment

## 📈 Potential Outcomes
Upon completion of this tool, logistics planners can:  
- Quickly compute optimal load sets for vehicles/ships  
- Avoid under-utilising capacity or overloading  
- Reduce fuel and transportation costs  
- Make informed decisions through a user-friendly web interface  

## 🚀 Deployment
To host it free via GitHub Pages:  
1. Go to your repository **Settings → Pages**  
2. Set **Source** to `main` branch, folder `/ (root)`  
3. Save and wait a moment  
4. Visit: `https://<YourGitHubUsername>.github.io/Logistics-Knapsack-Optimizer/`  

## 📂 Folder Structure (Example)

Logistics-Knapsack-Optimizer/
	│
	├── index.html
	├── README.md
	├── A6_Project_Logistics_Knapsack.pdf ← Project approval sheet/report
	├── scenario.json ← Example pre-saved scenario

## 🔧 Future Enhancements
- Add 3D stacking / orientation constraints for items  
- Visual cargo-load layout preview (bins/trucks)  
- Multi-vehicle allocation (split across multiple trucks)  
- Real-time live API data import for item weights/values  
- Server-based ILP solver for large scale dataset  

---

Thank you for exploring this project.  
Feel free to ⭐ the repo and drop any feedback or pull requests!

---

© 2025 Vivekananda Global University — CSE Department  
