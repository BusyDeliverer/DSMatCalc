Excellent! It's always a good idea to keep the documentation updated with the latest features. Based on all the changes we've made, here is a completely revised `README.md` file that accurately reflects the current state of your application.

---

# Death Stranding Material Unit Calculator

> A simple and intuitive web-based tool designed to help Porters in Death Stranding manage multiple construction projects, calculate material requirements, and track inventory with ease.

## About The Project

Ever find yourself juggling the material costs for paving multiple sections of road, or upgrading several structures at once? This tool solves that problem by moving beyond a single calculation and offering a full project management system.

The Death Stranding Material Unit Calculator helps you efficiently plan your resource gathering by allowing you to create and manage a list of projects. For each project, you specify the **total material needs**. Your **"You Have" inventory is global**, so you always know what's available in your private lockers. The calculator then shows the **net required amount** for your active project and breaks it down into the optimal number of in-game containers. When a project is finished, you can quickly update your inventory and even delete the project in one step. Keep on keeping on!

---

## ✨ Features

### Project Management
* **Multi-Project Support**: Create and manage an unlimited number of projects, perfect for tracking different road sections, zip-line networks, or structure upgrades.
* **Add, Rename, & Delete**: A dedicated sidebar allows you to easily add new projects, rename them on the fly with a pen icon, and delete them with a trash icon (complete with a confirmation step).
* **Persistent Projects & Inventory**: All your projects and your global inventory are saved to local storage, so your list is always there when you return.

### Material Calculation & Inventory
* **Per-Project Needs**: Enter the **Total Needed** amount for each material on a per-project basis.
* **Global Inventory**: The **"You Have"** fields represent your total available materials, shared across all projects.
* **Net Required Calculation**: Automatically determines the net amount of each material you still need to collect for the active project (`Total Needed - You Have`).
* **Optimal Unit Calculation**: Calculates the best breakdown of units (e.g., containers of 400, 200, 100) for the `Net Required` amount to meet or exceed your goal.
* **Waste Tracking**: Clearly displays any "wasted" material from using larger containers, helping you manage resources efficiently.

### Workflow Tools
* **"Project Finished" with Delete Option**: When a project is complete, a confirmation modal allows you to deduct the required materials from your inventory and gives you the option to **simultaneously delete the project**.
* **Reset Needed Materials**: A dedicated button clears *only* the "Total Needed" fields for the active project, allowing you to plan a new set of requirements without affecting your inventory.
* **Keyboard Shortcuts**: Speed up your workflow with intuitive keyboard shortcuts for all dialogs.

---

## 🚀 Getting Started

No installation is needed! Simply visit [https://busydeliverer.github.io/DSMatCalc/](https://busydeliverer.github.io/DSMatCalc/) or download the files.

1.  Download the project files to your local machine.
2.  Open the `index.html` file in your favorite web browser.

---

## 📖 How to Use

1.  **Add a Project**: Use the **+ Add** button in the sidebar to create your first project. If no projects exist, you can also use the large button in the center.
2.  **Select a Project**: Click on a project name in the sidebar to make it active. Its name will appear at the top of the calculator.
3.  **Enter Material Amounts**: Input the **Total quantity you Need** for the selected project. The **quantity you Have** represents your global inventory.
4.  **Add Amounts (Optional)**: Click the `+` button next to any input field to quickly add to its current value.
5.  **Calculate**: Click the **Calculate Units** button to see the breakdown. The page will automatically scroll to the results.
6.  **Manage Projects**: In the sidebar, click the **pen icon** to rename a project or the **trash can icon** to delete it.
7.  **Finish a Project**: Once complete, click the **Project Finished** button. In the dialog, confirm the action. You can also check the box to **delete the project** after its materials are deducted from your inventory.
8.  **Reset Needed Materials**: Click the **Reset needed materials** button or press `R` to clear the "Total Needed" inputs for the current project without affecting your inventory.

---

## ⌨️ Keyboard Shortcuts

### Global Shortcuts
* `R` (case-insensitive): Resets the "Total Needed" inputs for the active project (when no dialogs are open).

### Dialog Shortcuts (for all pop-up windows)
* `Enter`: Confirm the action (Save, Add, Confirm Delete, etc.).
* `Escape`: Cancel and close the dialog without making changes.
