# 🎨 Interactive Image Editor

A powerful, web-based image editing application built with HTML5, CSS3, and Fabric.js that allows users to create, manipulate, and customize images with an intuitive drag-and-drop interface.

![Interactive Image Editor](https://img.shields.io/badge/Status-Active-brightgreen) ![HTML5](https://img.shields.io/badge/HTML5-E34F26?logo=html5&logoColor=white) ![CSS3](https://img.shields.io/badge/CSS3-1572B6?logo=css3&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?logo=javascript&logoColor=black) ![Fabric.js](https://img.shields.io/badge/Fabric.js-FF6B6B?logo=javascript&logoColor=white)

## ✨ Features

### 🖼️ **Image Management**
- **Upload Images**: Click to browse or drag & drop images directly onto the canvas
- **Smooth Resizing**: Professional corner handles for proportional image scaling
- **Free Rotation**: Rotate images to any angle with intuitive controls
- **Perfect Positioning**: Drag images anywhere on the canvas with pixel precision

### 📝 **Text Editor**
- **Custom Text**: Add text with customizable colors and fonts
- **Live Editing**: Double-click text to edit directly on the canvas
- **Full Manipulation**: Move, resize, and rotate text elements just like images
- **Color Picker**: Choose from any color for your text elements

### 🎛️ **Canvas Controls**
- **Background Customization**: Change canvas background color instantly
- **Grid System**: Subtle grid overlay for perfect alignment
- **Multi-Selection**: Select multiple objects using Ctrl/Cmd + click
- **Keyboard Shortcuts**: Delete objects with Delete/Backspace keys

### 💾 **Project Management**
- **Save Projects**: Complete state preservation in memory
- **Load Projects**: Restore all objects, positions, and properties
- **Clear Canvas**: Quick reset functionality with confirmation
- **Export Ready**: Canvas can be easily exported to various formats

## 🚀 Getting Started

### Prerequisites
- Modern web browser with HTML5 Canvas support
- No additional installations required - runs entirely in the browser

### Installation
1. Clone this repository:
```bash
git clone https://github.com/thedev-goutam/Interactive-Image-Editor.git
```

2. Navigate to the project directory:
```bash
cd Interactive-Image-Editor
```

3. Open `index.html` in your web browser or serve it using a local web server:
```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
http-server

# Using PHP
php -S localhost:8000
```

4. Open your browser and go to `http://localhost:8000`

## 🎮 How to Use

### Basic Operations
1. **Add Images**: Click the "📷 Add Image" button or drag image files onto the canvas
2. **Select Objects**: Click on any image or text to select it (shows selection handles)
3. **Resize**: Drag corner handles to resize objects proportionally
4. **Move**: Click and drag selected objects to reposition them
5. **Rotate**: Use corner handles to rotate objects to any angle

### Text Features
1. Click "📝 Add Text" and enter your desired text
2. Choose text color using the color picker before adding
3. Double-click any text on the canvas to edit it inline
4. Text can be moved, resized, and rotated like images

### Advanced Features
- **Multi-Selection**: Hold Ctrl (Cmd on Mac) while clicking to select multiple objects
- **Keyboard Shortcuts**: Press Delete or Backspace to remove selected objects
- **Background Color**: Use the background color picker to customize canvas appearance
- **Save/Load**: Use the save and load buttons to preserve your work

## 🛠️ Technical Details

### Built With
- **HTML5 Canvas**: Core rendering technology
- **Fabric.js**: Advanced canvas manipulation library
- **CSS3**: Modern styling with gradients and animations
- **Vanilla JavaScript**: Pure JS for application logic

### Browser Support
- Chrome 60+
- Firefox 55+
- Safari 12+
- Edge 79+

### Architecture
- **Single Page Application**: Everything runs in one HTML file
- **No Backend Required**: Fully client-side application
- **Memory Storage**: Projects saved in browser memory (can be extended to localStorage)
- **Responsive Design**: Works on desktop and mobile devices

## 🎯 Use Cases

- **Social Media Graphics**: Create custom images for social platforms
- **Presentations**: Design slides and presentation materials
- **Digital Art**: Combine images and text for creative projects
- **Prototyping**: Quick mockups and design iterations
- **Educational Content**: Create visual learning materials
- **Marketing Materials**: Design simple promotional graphics

## 🔧 Customization

The editor is highly customizable. You can:
- Modify canvas dimensions in the HTML
- Adjust styling in the CSS section
- Add new tools and features by extending the JavaScript
- Integrate with backend services for permanent storage
- Add export functionality for different file formats

## 📱 Responsive Design

The application is fully responsive and works across different screen sizes:
- **Desktop**: Full feature set with optimal user experience
- **Tablet**: Touch-friendly interface with adapted controls
- **Mobile**: Core functionality preserved with mobile-optimized layout

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

### Ideas for Contributions
- Add more text formatting options (bold, italic, fonts)
- Implement shape drawing tools
- Add image filters and effects
- Create export functionality (PNG, JPG, SVG)
- Add undo/redo functionality
- Implement layers system

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- [Fabric.js](http://fabricjs.com/) - Powerful HTML5 canvas library
- [CDN.js](https://cdnjs.com/) - Fast and reliable CDN for Fabric.js
- Modern CSS techniques for beautiful UI design
- HTML5 Canvas API for rendering capabilities

## 📞 Support

If you have any questions or run into issues:
- Open an issue on GitHub
- Check the [Fabric.js documentation](http://fabricjs.com/docs/)
- Review the code comments for implementation details

---

**Made with ❤️ for the creative community**
