# Estrelas do Amanhã — Enrollment Form

Static enrollment (registration) form for "Estrelas do Amanhã" early childhood school. Built with semantic HTML and plain CSS as part of the Rocketseat Fullstack course.

## Features

- Semantic HTML5 structure
- Modular CSS files for styling
- Accessible markup (alt attributes, form labels)
- File upload (dropzone), custom radio/checkbox styles
- Clean and maintainable code

## Getting Started

### Prerequisites

- Modern web browser
- Local server (optional)

### Installation

1. Clone the repository:
```bash
git clone https://github.com/rachelmgaldino/school-enrollment-form.git
```

2. Enter the project folder:
```bash
cd school-enrollment-form
```

3. Open index.html in your browser or run a local server, for example:
```bash
npx http-server . -o
```

## Project Structure
```text
enrollment-form/
├── index.html
├── styles/
│   ├── index.css
│   ├── forms.css
│   ├── global.css
│   ├── layout.css
│   └── fields/
│       ├── index.css
│       ├── input.css
│       ├── droparea.css
│       ├── radio.css
│       ├── checkbox.css
│       └── buttons.css
├── assets/
│   ├── icons/
└── README.md
```

## Technical Details

- HTML: semantic structure with clear form fieldsets and labels
- CSS: variables for consistent theming, Flexbox/Grid for layout
- Accessibility: alt texts for images, labels for form controls, visible focus styles
- Performance: optimized images and clean CSS

## Acknowledgements

- [Rocketseat](https://rocketseat.com.br/) — course and challenge materials
- Icon/image credits as applicable (local assets)