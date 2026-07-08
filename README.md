# Rouleatte

[Rouleatte](https://rouleatte.netlify.app) is an interactive, browser-based meal generator styled as a slot machine. It randomises five core components of a dish to solve decision fatigue when planning meals.

<img width="2074" height="1162" alt="CleanShot 2026-07-08 at 14 57 57@2x" src="https://github.com/user-attachments/assets/ca42b372-5d08-480d-85fb-d933ad3e1e38" />

## Features

* **Spin Mechanism**: An animated lever triggers a sequential slot-spinning effect, stopping one by one for a cascading reveal.
* **Locking System**: Manually select and lock specific ingredients using a dropdown overlay. Locked slots bypass the spin phase.
* **Targeted Clearing**: Clear or reroll specific categories without resetting the entire board.
* **Responsive Design**: Adapts to fit narrow screens and mobile devices.

## Architecture & Data

The application constructs meals from five distinct categories:

| Category | Ingredients |
| :--- | :--- |
| **Meat** | Chicken, Minced Chicken, Beef, Minced Beef, Pork, Minced Pork, Lamb, Duck, Salmon, White Fish, Prawn, Squid |
| **Carbs** | Rice, Long Pasta, Short Pasta, Stuffed/Sheet Pasta, Potato, Bagel, Burger, Pizza, Bread, Udon, Rice Noodle, Wheat noodle, Egg noodle, Quinoa/Couscous, Tortilla Wrap |
| **Vegetable** | Broccoli, Cauliflower, Brussel Sprouts, Spinach, Corn, Cabbage, Asparagus, Zucchini, Tomato, Kang Kong, Kai Lan, Chye Sim, Bok Choy, Lady’s Finger, Pumpkin, Mushroom, Bell pepper, Cucumber, Carrot, Beansprout, Eggplant |
| **Flavour** | Salted Egg, Garlic Butter, Truffle, Tomato, Pesto, Lemon & Herb, Teriyaki, Miso, Gochujang, Curry, Black Pepper, Sweet & Sour, Cajun, Mala, Sambal, Tomyum, Creamy/Cheese |
| **Method** | Stir-fried, Deep-fried, Grilled, Roasted/Baked, Steamed, Boiled/Poached, Braised |

## Usage Example

Assume you have leftover beef in the fridge that must be cooked today, but you have no idea what you can do with it.

1. Click the "Meat" slot and manually select "Beef". The slot locks and turns light green.
2. Click the lever to spin the slot machine. The Meat slot remains fixed on "Beef".
3. The remaining four slots spin and resolve.
4. The machine outputs a complete meal concept: "Beef", "Udon", "Spinach", "Teriyaki", and "Stir-fried".
5. Enjoy your delicious meal!

## Try it now!
[rouleatte.netlify.app](https://rouleatte.netlify.app)
