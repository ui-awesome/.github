# UI Awesome: The Frontend Layer for Modern PHP

[![Flowbite](https://img.shields.io/badge/Flowbite-38B2AC?style=for-the-badge&logo=flowbite&logoColor=white)](https://flowbite.com)
[![Tailwind CSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=for-the-badge&logo=tailwind-css&logoColor=white)](https://tailwindcss.com)
[![Bootstrap 5](https://img.shields.io/badge/Bootstrap_5-7952B3?style=for-the-badge&logo=bootstrap&logoColor=white)](https://getbootstrap.com)
[![daisyUI](https://img.shields.io/badge/daisyUI-23272A?style=for-the-badge&labelColor=23272A&color=23272A&logoColor=white&fontColor=white)](https://daisyui.com)

**UI Awesome** provides the missing link between **PHP backends** and modern **frontend frameworks**.

We build fluid HTML generators, form field widgets, and framework-agnostic models whose markup fits any CSS framework.

## 🎨 Why UI Awesome?

Writing raw HTML inside PHP strings is messy and error-prone.

UI Awesome offers an object-oriented, fluent interface to generate complex UI components without leaving your PHP classes.

## 🧩 Core Libraries

| Library                                                    | Description                                        | Tech Stack           |
| :--------------------------------------------------------- | :------------------------------------------------- | :------------------- |
| **[HTML](https://github.com/ui-awesome/html)**             | Fluid, immutable HTML5 tag generation              | `PHP` `HTML5`        |
| **[HTML Field](https://github.com/ui-awesome/html-field)** | Form fields bound to a model, with label and error | `PHP` `Forms`        |
| **[Model](https://github.com/ui-awesome/model)**           | Typed model mapping, framework-agnostic            | `PHP` `Data Binding` |
| **[Form Model](https://github.com/ui-awesome/form-model)** | Form metadata and validation errors                | `PHP` `Validation`   |

## 💻 Usage Example

```php
use UIAwesome\Html\Form\Button;

// Create a styled button in pure PHP.
echo Button::tag()
    ->class('bg-blue-500 hover:bg-blue-700 text-white font-bold py-2 px-4 rounded')
    ->content('Subscribe')
    ->render();
```

## 🌐 Part of the Ecosystem

Maintained by the core team of [yii2-framework](https://github.com/yii2-framework) and [yii2-extensions](https://github.com/yii2-extensions).

---

<div align="center">
  <a href="https://github.com/sponsors/terabytesoftw">
    <img src="https://img.shields.io/badge/Sponsor-Click%20Here-pink?style=for-the-badge&logo=github-sponsors" height="40" alt="Sponsor on GitHub"/>
  </a>
</div>
