# Client Management Dashboard

A responsive dashboard for managing client relationships and data visualization. This dashboard includes customizable views, filtering capabilities, and a modern user interface built with web components.

![Client Management Dashboard](https://via.placeholder.com/800x400?text=Client+Management+Dashboard)

## Features

- **Responsive Layout**: Optimized for desktop, tablet, and mobile devices
- **Client Overview Cards**: Quick stats and recent activity widgets
- **Client Data Table**: Sortable and filterable client information
- **Customizable Views**: Advanced filtering and column customization
- **Saffron Components Integration**: Leveraging Thomson Reuters design system
- **Accessibility Support**: WCAG compliant with keyboard navigation and screen reader support

## Customization Panel

The dashboard includes a powerful customization panel accessible via the "Customize View" button in the header. This panel allows users to:

- Filter client data using advanced "If/Then" logic
- Customize visible columns in the client table
- Save and apply custom views
- Apply complex condition-based filtering

## Tech Stack

- **Frontend**:
  - HTML5
  - CSS3 (with responsive design)
  - JavaScript (ES6+)
  - Saffron Web Components (@saffron/core-components)
  - Saffron Design System Styles (@saffron/core-styles)
  - Font Awesome icons

- **Backend**:
  - Node.js
  - Express.js

## Project Structure

```
client-mgmt-test/
├── package.json        # Project dependencies and scripts
├── server.js           # Express server configuration
└── public/             # Static assets
    ├── index.html      # Main HTML structure
    ├── css/
    │   └── styles.css  # Custom styles
    ├── js/
    │   └── main.js     # JavaScript functionality
    └── images/         # Image assets
```

## Getting Started

1. Install dependencies:
```
npm install
```

2. Start the development server:
```
npm run dev
```

3. Open a browser and navigate to:
```
http://localhost:3000
```

## Accessibility Features

This application follows WCAG 2.1 A and AA guidelines, including:

- Proper semantic HTML structure
- ARIA attributes where appropriate
- Keyboard navigation support
- Screen reader compatibility
- Focus management
- High contrast support
- Reduced motion settings support

## Saffron Components Used

The dashboard leverages the following Saffron web components:

- `tr-navigation` & `tr-navigation-item`: For the sidebar menu
- `tr-button`: For action buttons throughout the interface
- `tr-card`: For content containers
- `tr-table`: For displaying client data
- `tr-badge`: For status indicators
- `tr-pagination`: For table pagination
- `tr-select`: For filtering controls
- `tr-icon`: For various icons throughout the interface
- `tr-avatar`: For user profile
- `tr-logo`: For Thomson Reuters branding

## Development

### Available Scripts

- `npm start`: Starts the production server
- `npm run dev`: Starts the development server with auto-reload
- `npm test`: Runs test scripts (placeholder)

## Design Principles

This dashboard follows these key design principles:

1. **Simplicity**: Clean, uncluttered interface focused on content
2. **Consistency**: Unified visual language across all components
3. **Hierarchy**: Clear visual hierarchy guiding users through the interface
4. **Feedback**: Interactive elements provide clear feedback
5. **Accessibility**: Designed to be usable by everyone

## Keyboard Navigation

The dashboard supports full keyboard navigation:

- Tab: Navigate between interactive elements
- Enter/Space: Activate buttons and controls
- Escape: Close modal dialogs and menus
- Arrow keys: Navigate within components like tables and dropdown menus

## Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)

## License

This project is licensed under the ISC License - see the LICENSE file for details.

## Acknowledgments

- Thomson Reuters Saffron Design System
- Font Awesome for icons
- Express.js team

## Agent Change Log

2025-04-18 10:00 AM CDT
- Implemented the "Customize View" modal panel according to Figma design specifications
- Added CSS styles for the new customization interface
- Created JavaScript functionality for modal interaction and customization features
- Updated package.json to include Font Awesome for icons
- Improved accessibility with keyboard navigation support