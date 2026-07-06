<div align="center">

# Front-End Assignment - techHive Store

Responsive e-commerce website for gaming and tech products, copied from the TechHive group source and documented with submitted Group 44 evidence.

![HTML](https://img.shields.io/badge/HTML-Static%20Pages-E34F26?style=for-the-badge&logo=html5&logoColor=white)
![CSS](https://img.shields.io/badge/CSS-Responsive%20Styling-1572B6?style=for-the-badge&logo=css3&logoColor=white)
![JavaScript](https://img.shields.io/badge/JavaScript-Store%20Interactions-F7DF1E?style=for-the-badge&logo=javascript&logoColor=111827)
![Bootstrap](https://img.shields.io/badge/Bootstrap-UI%20Components-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)
![License](https://img.shields.io/badge/License-MIT-111827?style=for-the-badge)

</div>

---

## Table of Contents

- [About](#about)
- [Live Site](#live-site)
- [Problem Scope](#problem-scope)
- [Features](#features)
- [Pages](#pages)
- [My Contribution](#my-contribution)
- [Repository Structure](#repository-structure)
- [License](#license)

## About

This repository is the public portfolio copy of the UCCD2323 Front-End Web Development Group 44 assignment. The project is **techHive Store**, a responsive static e-commerce website for PC peripherals and gaming products.

The source is copied from the original group repository:

```text
https://github.com/techhive1957-code/front-end-assignment
```

The local coursework submission package was used as evidence for the project title, group details, website URL, and contribution breakdown.

## Live Site

Submitted website URL:

```text
https://techhive1957-code.github.io/front-end-assignment/index.html
```

## Problem Scope

techHive Store is designed around a realistic e-commerce flow: visitors should be able to browse products, compare close alternatives, view product details, manage a cart, and proceed through checkout with clear RM pricing.

The site also supports modern shopping helpers such as recently viewed products, comparison storage, product filtering, and a guide page that remembers user preferences.

## Features

- Responsive multi-page storefront.
- Product listing and bestseller pages.
- Product detail page with specifications, fit/grip guidance, recommendations, and recently viewed products.
- Product comparison with a maximum of three selected items.
- Cart and checkout flow with local client-side state.
- Login and signup pages.
- Guide, about, and contact pages.
- Product catalog stored in `products.json`.
- Local storage, session storage, and cookies for interaction state such as cart, recently viewed items, compare list, theme, and guide preferences.

## Pages

| Page | Purpose |
|---|---|
| `index.html` | Homepage and main navigation entry |
| `shop.html` | Product browsing, filters, and product cards |
| `bestseller.html` | Best-selling product section |
| `product-detail.html` | Product images, specs, fit guide, recommendations |
| `compare.html` | Side-by-side comparison for selected products |
| `cart.html` | Cart review and item quantity flow |
| `checkout.html` | Order summary and payment form |
| `login.html` | Login page |
| `signup.html` | Registration page |
| `guide.html` | Shopping guide and preference helper |
| `about.html` | Store background page |
| `contact.html` | Contact and support page |

## My Contribution

The submitted report identifies **Koo Ian Hong** as contributing:

- `product-detail.html`
- `compare.html`
- `guide.html`

The evidence summary is stored in [docs/project-evidence.md](docs/project-evidence.md).

## Repository Structure

```text
front-end-assignment/
|-- css/                 Stylesheets and Bootstrap assets
|-- img/                 Product and layout images
|-- js/                  Cart, product, compare, and shop logic
|-- docs/
|   `-- project-evidence.md
|-- products.json        Product catalog data
|-- index.html
|-- shop.html
|-- product-detail.html
|-- compare.html
|-- cart.html
|-- checkout.html
|-- guide.html
|-- LICENSE
`-- README.md
```

## License

This repository is released under the MIT License. See [LICENSE](LICENSE) for details.
