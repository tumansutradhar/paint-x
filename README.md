# PaintX

A modern digital drawing application built with React and Tailwind CSS. Create, draw, and export your artwork with advanced brush controls and PDF export functionality.

## About The Project

PaintX is a feature-rich drawing application for digital artists and casual users:
- What it solves: Provides an accessible, web-based drawing platform with essential tools for sketching, painting, and exporting artwork
- What makes it unique: Real-time canvas rendering with adjustable brush properties, undo/redo functionality, and PDF export capability using jsPDF
- What was learned: React canvas manipulation, state management for drawing tools, PDF generation, Tailwind CSS responsive design, and performance optimization for graphics rendering

The application features a responsive canvas interface with customizable drawing tools, color selection, brush opacity control, and the ability to save artwork as PDF files.

## Built With

- React 19.0.0
- Vite 6.2.0
- Tailwind CSS 4.0.9
- jsPDF 3.0.0 (PDF export)
- Google Fonts (Inter typeface)

## Getting Started

### Prerequisites

- Node.js and npm installed on your system

### Installation

1. Clone the repo
   ```bash
   git clone https://github.com/tumansutradhar/paint-x.git
   cd paint-x
   ```

2. Install dependencies
   ```bash
   npm install
   ```

3. Start the development server
   ```bash
   npm run dev
   ```

4. Open in your browser
   ```
   http://localhost:5173/
   ```

## Usage

**Drawing Tools:**
1. Click and drag on the canvas to draw
2. Adjust brush size using the line width slider
3. Choose brush color with the color picker
4. Control brush opacity with the opacity slider
5. Use the eraser tool to remove parts of your drawing

**Canvas Management:**
- Undo/Redo functionality to manage drawing history
- Clear canvas to start fresh
- Save your artwork as a PDF file
- Full-screen drawing experience with responsive controls

Example workflow:
```
1. Open PaintX in your browser
2. Customize brush settings (color, size, opacity)
3. Draw on the canvas using mouse/touchpad
4. Use Undo/Redo to perfect your artwork
5. Export as PDF or continue editing
```

## Features

- Full-featured digital canvas with responsive rendering
- Adjustable brush size, color, and opacity
- Color picker for precise color selection
- Eraser tool for non-destructive editing
- Undo/Redo functionality with drawing history
- PDF export capability using jsPDF
- Menu and Footer components for UI organization
- Error boundary for error handling
- High DPI/Retina display support
- Responsive design with Tailwind CSS
- Smooth drawing experience with round line caps and joins

## Project Structure

```
paint-x/
├── src/
│   ├── components/
│   │   ├── Menu.jsx (Drawing tools interface)
│   │   └── Footer.jsx (Footer component)
│   ├── App.jsx (Main drawing application)
│   ├── App.css
│   ├── index.css
│   ├── main.jsx
│   └── ErrorBoundary.jsx
├── public/ (Static assets)
├── index.html
├── vite.config.js
├── tailwind.config.js
└── package.json
```

## Roadmap

- [x] Basic drawing functionality
- [x] Brush color customization
- [x] Brush size adjustment
- [x] Opacity control
- [x] Undo/Redo functionality
- [x] PDF export
- [x] Eraser tool
- [ ] Shape drawing tools (rectangle, circle, line)
- [ ] Text annotation tool
- [ ] Layer support
- [ ] Brush presets and custom brushes
- [ ] Save/Load drawings in app format
- [ ] Touch support optimization
- [ ] Performance improvements for large canvases

## Contributing

Contributions are what make the open-source community such an amazing place to learn, inspire, and create. Any contributions you make are **greatly appreciated**.

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

Distributed under the MIT License. See `LICENSE.md` for more information.

## Contact

Tuman Sutradhar

- GitHub: [@tumansutradhar](https://github.com/tumansutradhar)
- Email: connect.tuman@gmail.com
- LinkedIn: [Tuman Sutradhar](https://www.linkedin.com/in/tumansutradhar/)

Project Link: [https://github.com/tumansutradhar/paint-x](https://github.com/tumansutradhar/paint-x)

## Acknowledgments

- React documentation and tutorials
- Tailwind CSS framework
- jsPDF library for PDF export
- Google Fonts for typography
