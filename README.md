# Royal Hotel Service (8086 Assembly Language)

A menu-driven system written in **Assembly Language (x86)** designed to run on the **EMU8086** emulator. This program allows users to select rooms or various food items, input quantities, track orders, and generate a final structured sales report with total billing.

## 📋 Features
- **Interactive Menu:** Room booking and multiple food options (Pasta, Burger, Noodles, Shake, Chicken Roll).
- **Quantity Selection:** Dynamically accepts item quantities from 1 to 9.
- **Real-time Sales Report:** Displays total items sold individually and computes the aggregate bill dynamically.
- **Output Algorithm:** Includes a custom multi-digit decimal printing routine for showing large total bills correctly on the console.

## 💰 Menu & Pricing Card
| Item No. | Item Name | Price (Per Unit) |
| :--- | :--- | :--- |
| 1 | Rooms | 500 |
| 2 | Pasta | 300 |
| 3 | Burger | 250 |
| 4 | Noodles | 200 |
| 5 | Shake | 150 |
| 6 | Chicken Roll | 180 |

## 🚀 How to Run
1. Download and install **EMU8086 Emulator**.
2. Create a new file and paste the code from `Hotel Management System.asm` into the emulator editor.
3. Click on the **Emulate** button at the top.
4. Click **Run** to execute the program in the terminal screen.
