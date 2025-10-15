# 🎨 Color Detector — Pastel Edition

A lightweight and interactive **Color Detection Tool** built with **HTML, CSS, and JavaScript**.  
This pastel-themed website allows users to **upload an image** and **click anywhere** to instantly detect the color at that pixel.  
It displays the **RGB value**, **HEX code**, and the **closest color name** from a predefined dataset.

---

## 🚀 Features

- Upload an image from your device
- Click anywhere on the image to detect the color
- Displays:
  - RGB values
  - HEX code
  - Closest known color name
- Copy HEX value with one click
- Clean pastel-themed UI

---

## 🖼️ Demo

> Click on an image to detect color at that pixel. The selected color appears in a swatch, with RGB and HEX displayed next to it.

---

## 🧩 How It Works

1. The user uploads an image.
2. The image is drawn onto an HTML `<canvas>`.
3. Clicking anywhere on the image reads the pixel's RGB values.
4. Converts the RGB to HEX format.
5. Finds the nearest color name from the built-in color dataset.
6. Updates the UI with color swatch, name, and codes.

---

## 🗂️ Project Structure

```
Color-Detector-Pastel
│
├── index.html       # Main website with HTML, CSS, JS
├── colors.csv       # Color dataset (name, RGB, HEX)
└── README.md        # Project documentation
```

---

## ⚙️ How to Run Locally

1. Clone the repository:
```bash
git clone https://github.com/<your-username>/Color-Detector-Pastel.git
cd Color-Detector-Pastel
```

2. Open `index.html` in any modern browser (Chrome, Firefox, Edge).

3. Upload an image and click on any point to detect the color.

---

## 🌐 Deployment

- **GitHub Pages**: Simply enable GitHub Pages in the repo settings.
- **Render**: Deploy as a static site — no backend required.

---

## 📚 Color Dataset

The project uses a small **colors.csv** dataset to map RGB to color names.  
It can be expanded with more colors as needed.

---

## 💡 Future Improvements

- Support **paste image URLs** from Google Photos or other sources
- Include **color history** or **multiple pinned colors**
- Add **zoom/magnifier** for precise pixel selection

---

## 🧑‍💻 Author

**Jashwanth**  
Designed for designers, developers, and artists.  
Built with 💛 in HTML, CSS, and JavaScript.
