# PDF Reviewer PWA

A Progressive Web Application for viewing and annotating PDF documents with multi-document support and collaborative features.

![PDF Reviewer PWA Main Interface](screenshots/main-interface.png)

*Main interface showing multiple PDF documents with annotations*

## Features

### Implemented ✅

#### File System Management
- Multiple PDF document support with hierarchical directory structure
- Drag & drop file management
- File search functionality with wildcard support
- File system watching and auto-refresh

#### PDF Viewer
- Multi-document viewing with independent scaling
- Dynamic document positioning
- Page navigation and thumbnail preview
- Customizable zoom levels per document

#### Layer Management
- Layer creation and deletion
- Layer visibility toggle
- Layer locking mechanism
- Layer reordering via drag and drop

#### Data Persistence
- IndexedDB implementation for local storage
- Project save/load functionality
- Project export/import capabilities
- File structure persistence

![Layer Management Interface](screenshots/layer-management.png)
*Layer management panel showing multiple layers with visibility and lock controls*

### In Progress 🚧

#### Shape Drawing (70% Complete)
- Basic shapes (rectangle, circle, arrow, line)
- Text input and editing
- Shape selection and manipulation
- Style configuration
- Preview display optimization (pending)
- Shape snapping (pending)

#### Document Linking (50% Complete)
- Link creation UI
- Link visualization
- Link navigation (pending)
- Link property editing (pending)

#### Performance Optimization (30% Complete)
- Rendering optimization
- Memory usage monitoring
- Large PDF optimization (pending)
- Caching strategy implementation (pending)

### Planned Features 📋

#### Shape Drawing Enhancements
- Constrained drawing with shift key
- Snap guides
- Dimension display
- Shape templates
- Custom shape library

#### Advanced Linking
- Jump navigation
- Back/forward navigation
- Link map visualization
- Custom link icons
- Link validation

#### User Experience
- Keyboard shortcuts
- Command palette
- Dark mode support
- Custom themes
- Responsive design

![Shape Drawing Tools](screenshots/shape-tools.png)
*Shape drawing toolbar with style configuration options*

## Technical Stack

- React 18
- TypeScript
- Zustand for state management
- PDF.js for PDF rendering
- IndexedDB for local storage
- File System Access API
- Web Workers for performance
- Service Workers for offline support

## Project Structure

```
src/
├── app/                 # Application core
├── components/         # React components
├── features/          # Feature implementations
├── hooks/             # Custom React hooks
├── utils/             # Utility functions
└── types/             # TypeScript definitions
```

## Getting Started

1. Clone the repository:
```bash
git clone https://github.com/yourusername/pdf-reviewer-pwa.git
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm start
```

4. Build for production:
```bash
npm run build
```

## Browser Support

- Chrome/Edge (latest)
- Firefox (latest)
- Safari (latest)

Note: File System Access API support varies by browser.

![Browser Support](screenshots/browser-support.png)

*Browser compatibility matrix showing feature support*

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Acknowledgments

- PDF.js team for the PDF rendering engine
- React team for the fantastic framework
- Contributors and testers who have helped shape this project

---

For more information, please visit our [documentation site](https://docs.example.com).
