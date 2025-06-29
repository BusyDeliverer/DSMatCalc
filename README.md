Here's the updated `README.md` with that clarification:

# Death Stranding Material Unit Calculator

> A simple and intuitive web-based tool designed to help Porters in Death Stranding calculate and manage the required units of various materials, complete with features for easy input management, inventory tracking, and project completion.

## About The Project

Ever find yourself at a terminal needing to fabricate or upgrade a structure, but you're not sure exactly how many containers of Metals or Ceramics to grab from your private locker? This tool solves that problem.

The Death Stranding Material Unit Calculator helps you efficiently plan your resource gathering by allowing you to specify both your **total material needs** and **how much you currently possess**. It then calculates the **net required amount** and breaks it down into the optimal number of in-game units (e.g., containers of 400, 200, 100, 50). It also tracks any "wasted" materials from procurement. When a project is finished, you can quickly update your inventory. Keep on keeping on!

---

## ✨ Features

* **Material Input**: Enter the **Total Needed** amount for Resins, Metals, Ceramics, Chemicals, Special Alloys, and Chiral Crystals. Additionally, input the **amount you currently Have** for each material.
* **Net Required Calculation**: Automatically determines the net amount of each material you still need to collect (`Total Needed - You Have`, not going below zero).
* **Optimal Unit Calculation**: Calculates the best breakdown of units for the `Net Required` amount to meet or exceed your goal.
* **Waste Tracking**: Clearly displays any "wasted" material (the excess amount beyond your exact need) from procurement, helping you manage resources efficiently in the UCA.
* **"Add Amount" Functionality**: Each input field (both "Needed" and "Have") has a `+` button that opens a dialog, allowing you to quickly add a specific quantity to its current value.
* **Project Finished**: Click this button to subtract the `Total Needed` amount from your "You Have" inventory (without going below zero) and reset the "Total Needed" fields to zero for a new project. Includes a confirmation dialog.
* **Reset Needed Materials**: A dedicated "Reset needed materials" button clears *only* the "Total Needed" input fields and calculation results, leaving your "You Have" inventory untouched.
* **Local Storage Persistence**: Your "Total Needed" and "You Have" inventory amounts are automatically saved to your browser's local storage, persisting even if you close and reopen the page.
* **Responsive Design**: Optimized for a seamless experience across desktop, tablet, and mobile devices.
* **Keyboard Shortcuts**: Speed up your workflow with intuitive keyboard shortcuts.

---

## 🚀 Getting Started

No installation is needed! Simply visit [https://busydeliverer.github.io/DSMatCalc/](https://busydeliverer.github.io/DSMatCalc/) or download the files.

1.  Download the project files to your local machine.
2.  Open the `index.html` file in your favorite web browser.

---

## 📖 How to Use

1.  **Open the Application**: Open [https://busydeliverer.github.io/DSMatCalc/](https://busydeliverer.github.io/DSMatCalc/) or the downloaded `index.html` file in your web browser.
2.  **Enter Material Amounts**: Input the **Total quantity you Need** for each material into the respective fields. Optionally, input the **quantity you currently Have**.
3.  **Add Amounts (Optional)**: Click the `+` button next to any input field (either "Needed" or "Have") to open the "Add Amount" dialog. Enter the amount you wish to add and click "Add" or press `Enter` on your keyboard.
4.  **Calculate**: Click the **Calculate Units** button to see the unit breakdown, net required amounts, and any wasted material.
5.  **Project Finished**: Once you've finished **building everything you needed** for a project, click the **Project Finished** button. Confirm the action to subtract the project's "Total Needed" from your "You Have" inventory and clear the "Total Needed" fields.
6.  **Reset Needed Materials**: Click the **Reset needed materials** button or press `R` on your keyboard to clear *only* the "Total Needed" inputs and results, allowing you to plan a new project without losing your current inventory.

---

## ⌨️ Keyboard Shortcuts

### Global Shortcuts
* `R` (case-insensitive): Press anywhere on the page (when no dialogs are open) to reset only the "Total Needed" inputs and clear results.

### "Add Amount" Dialog
* `Enter`: Confirm and add the entered amount.
* `Escape`: Cancel and close the dialog without making changes.
