# 🛍️ Shopify Product Variant Customization

## 📖 Overview

This project customizes the **Shopify Dawn Theme** to display **each color variant as an individual product** on collection pages instead of grouping all color options under a single product card.

This improves product visibility and makes it easier for customers to browse different color options directly from the collection page.

---

## 🎯 Problem Statement

By default, Shopify Dawn displays one product card regardless of how many color variants a product has.

Example:

- Women's Long Cardigan
  - White
  - Green
  - Blue
  - Red

Customers must open the product page before seeing available colors.

---

## ✅ Solution

This customization displays **each color variant as its own product card** on the collection page.

Instead of showing:

```
Women's Long Cardigan
```

The collection page displays:

```
Women's Long Cardigan - White
Women's Long Cardigan - Green
Women's Long Cardigan - Blue
Women's Long Cardigan - Red
```

Each card uses the correct image, title, and pricing.

---

# ✨ Features

- Display color variants as separate products
- Dynamic rendering using Shopify Liquid
- Responsive Shopify Dawn theme
- Uses variant-specific images
- Improved shopping experience
- Compatible with Shopify Online Store 2.0

---

## 🔧 Key Customizations

- Customized the Shopify Dawn theme using Liquid templates.
- Displayed each product color variant as an individual product card.
- Rendered variant-specific images and pricing dynamically.
- Preserved responsive behavior of the original Dawn theme.

---

# 🛠️ Technologies Used

- Shopify Liquid
- HTML5
- CSS3
- JavaScript
- Shopify JSON Templates

---

# 📁 Project Structure

```
shopify-product-variant-customization/
│
├── assets/
├── config/
├── layout/
├── locales/
├── sections/
├── snippets/
├── templates/
└── README.md
```

---

# 🖼️ Screenshots

## Original Product

The original product contains multiple color variants.

![Original Product](screenshots/original-product.jpg)

---

## Customized Collection Page

Each color variation is displayed as an individual product.

![Collection Page](screenshots/color-variants-page.jpg)

---

# ⚙️ How It Works

The customization:

- Reads all available product variants.
- Identifies color options.
- Retrieves the corresponding variant image.
- Creates an individual product card for every color variant.
- Displays variant title and price on the collection page.

---

# 🚀 Installation

Clone the repository

```bash
git clone https://github.com/Sulupk/shopify-product-variant-customization.git
```

Open the project

```bash
cd shopify-product-variant-customization
```

Upload the theme to a Shopify Development Store or preview using Shopify CLI.

---

# 🔮 Future Improvements

- Quick View support
- Variant filtering
- Size + Color combinations
- Lazy loading
- Performance optimization

---

# 👩‍💻 Author

**Sulu Padma Kumar**

GitHub:
https://github.com/Sulupk

---

# 📜 License

This project is shared for learning and portfolio purposes.