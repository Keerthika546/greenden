# 🌿 Greenden – Botanical Den & Modern Nursery

A responsive nursery website built with **HTML** and **Tailwind CSS**. Greenden lets visitors browse plants by category: vegetable seeds, bulbs, flowers and herbs.

## ✨ Features

- Responsive navbar with the Greenden logo and a mobile menu
- Category cards with round images (Herbs, Flowers, Bulbs, Pulses & Grains)
- Product sections for vegetable seeds, bulbs, flowers and herbs
- Uniform plant images (200×250 px) in a responsive grid
- Mobile-first layout built with Tailwind utility classes

## 🛠️ Tech Stack

| Area | Technology |
|---|---|
| Markup | HTML5 |
| Styling | Tailwind CSS |
| Images | JPG / PNG (optimized for the web) |

## 📁 Project Structure

```
greenden/
├── index.html
├── images/
│   ├── logo/            # Greenden logo (horizontal, icon-only, stacked)
│   ├── categories/      # 200×200 category images (shown round)
│   ├── vegetables/      # 200×250 plant images
│   ├── bulbs/           # 200×250 plant images
│   ├── flowers/         # 200×250 plant images
│   └── herbs/           # 200×250 plant images
└── README.md
```

> Adjust the folder names above to match your actual project.

## 🚀 Getting Started

1. **Clone the repository**
   ```bash
   git clone https://github.com/<your-username>/<your-repo-name>.git
   cd <your-repo-name>
   ```

2. **Open the site**
   - Open `index.html` in your browser, or
   - Use the **Live Server** extension in VS Code for auto-reload.

3. **Tailwind CSS**
   - If you use the Tailwind CDN, no install is needed. It is loaded in the `<head>` of `index.html`.
   - If you use the Tailwind CLI, run:
     ```bash
     npm install
     npx tailwindcss -i ./src/input.css -o ./dist/output.css --watch
     ```

## 🖼️ Image Guidelines

| Use | Size | Notes |
|---|---|---|
| Plant / product images | 200 × 250 px | `object-cover` keeps the shape without stretching |
| Category images | 200 × 200 px | Shown as circles with `rounded-full` |
| Logo (navbar) | height 32–40 px | Transparent PNG, use `w-auto` to keep proportions |

Example:

```html
<img src="./images/categories/herbs-mortar.jpg" alt="Herbs"
     class="aspect-square w-full max-w-[200px] rounded-full bg-white p-1 object-cover">
```

## 🗺️ Roadmap

- [ ] Product detail pages
- [ ] Search and filter by plant category
- [ ] Cart and enquiry form
- [ ] Backend integration (Java / Spring Boot)

## 🤝 Contributing

Suggestions and improvements are welcome. Fork the repo, create a branch, and open a pull request.

## 👩‍💻 Author

**Keerthika Selvam**
- GitHub: [@Keerthika546](https://github.com/Keerthika546)
- LinkedIn: [keerthika-selvam-](https://www.linkedin.com/in/keerthika-selvam-/)

## 📄 License

This project is for learning and portfolio purposes. Add a license (for example MIT) if you plan to share it publicly.

## 🙏 Image Credits

Plant photos are from free-to-use sources such as Pexels, Unsplash and Pixabay. Check the license of each image before using the site commercially.
