Here is a simple, clean README.md file for your project.

---

# Charybdis Keyboard Trainer

A lightweight, browser-based tool designed to help users learn and practice the layout of the **Charybdis** ergonomic split keyboard.

## 🌟 Features

* **3D Visualizer:** Simulates the split, tented, and columnar stagger of the physical keyboard using CSS 3D transforms.
* **Layer Training:** Practices keys across Base, Lower, and Raise layers.
* **Interactive Game Loop:** prompts you to press specific keys and tracks mistakes.
* **Smart Hints:** Automatically highlights the correct key and layer toggle (thumb cluster) after 3 failed attempts.
* **Real-time Feedback:** Visual feedback when you press physical keys on your keyboard.
* **Zero Dependencies:** Runs entirely in a single HTML file.

## 🚀 How to Use

1. Download the `index.html` file.
2. Open the file in any modern web browser (Chrome, Firefox, Edge, Safari).
3. Click the **Start / Reset** button.
4. Type the character requested in the box.

## 🎮 Controls

The trainer maps standard QWERTY keyboard inputs to the Charybdis layout logic:

* **Alpha Keys:** Standard QWERTY mapping.
* **Thumb Cluster (Left):** Space, Backspace, Lower Layer (mapped to `Fn` or specific keys based on your OS).
* **Thumb Cluster (Right):** Enter, Delete, Raise Layer.

## 🛠️ Customization

To modify the keymap, simply open `index.html` in a text editor and look for the `leftKeysData` and `rightKeysData` arrays within the `<script>` tag.

## 📄 License

Open source. Feel free to modify and distribute.
