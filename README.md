# IDEAS-frontend-sample-interview
design a frontend

# Frontend Interview Challenge — Coin Flip UI

Welcome! Your task is to design and implement a **simple frontend application** that simulates a coin flip experience.  
This project mirrors the backend challenge, but here you will focus only on **UI, state management, and interactivity**.  

You may use **any frontend stack** (Vanilla JS, React, Vue, Svelte, etc.). Keep it simple, clean, and easy to run locally.

---

## 📋 Requirements

### Core Features (required)

1. **Flip Once Button**
   - A button labeled `Flip Once`.
   - When clicked, simulate a random coin flip (`heads` or `tails`) and display the result clearly on the screen.

2. **Flip Multiple Times Button**
   - A number input (`count`) where the user specifies how many times to flip (between **1 and 100**).
   - A button labeled `Flip Multiple Times`.
   - When clicked, simulate that many flips and display:
     - Total heads
     - Total tails

3. **History Table**
   - Maintain a history of all flips.
   - For each row in the table, display:
     - **Action** (`single flip` or `multiple flips`)
     - **Result** (`heads` / `tails` for single, or `{heads: x, tails: y}` for multiple)

---

## ✅ Functional Rules

- The coin should be **fair** (50/50).
- Use client-side randomness (`Math.random()` or equivalent).
- All flips should update the **history table**.
- No actual API calls are needed — simulate the behavior entirely in the frontend.

---

## 🔧 Non-Functional Expectations

- Clear **UI layout** with buttons, inputs, and results displayed intuitively.
- Table should **append results** (don’t overwrite).
- Brief inline comments explaining major logic.
- Project should be **easy to run** (no heavy setup required).

---

## 🧪 Example Flow

1. User clicks **Flip Once**  
   - Result: `heads`  
   - Table entry:  
     | Action       | Result |
     |--------------|--------|
     | Single Flip  | heads  |

2. User enters `5` in input, clicks **Flip Multiple Times**  
   - Result: `{ heads: 3, tails: 2 }`  
   - Table entry:  
     | Action            | Result             |
     |-------------------|--------------------|
     | Multiple (5 flips)| heads: 3, tails: 2 |

---

## 🗂️ Suggested Project Layout

> Adapt to your framework/library of choice.
