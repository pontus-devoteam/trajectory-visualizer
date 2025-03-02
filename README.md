# OpenHands Trajectory Visualizer

A modern web application for visualizing OpenHands Resolver and their execution trajectory.

![Trajectory Visualizer](https://i.postimg.cc/VL4VYLbT/image.png)

## Features

- **GitHub Authentication**: Secure GitHub token authentication with appropriate scopes
- **Repository Selection**: Easy navigation between repositories
- **Workflow Run Timeline**: Interactive timeline visualization of workflow execution steps
- **Dark/Light Mode**: Full support for system and user preferences
- **Responsive Design**: Works seamlessly on desktop and mobile devices
- **Keyboard Navigation**: Efficient keyboard shortcuts for timeline traversal

## Getting Started

### Prerequisites

- Node.js (v16 or higher)
- npm or yarn

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/All-Hands-AI/trajectory-visualizer.git
   cd trajectory-visualizer
   ```

2. Install dependencies:
   ```bash
   # Install frontend dependencies
   npm install
   ```

3. Start the development server:
   ```bash
   npm start
   ```

4. Open [http://localhost:3000](http://localhost:3000) in your browser

### GitHub Token Setup

To use Trajectory Visualizer, you'll need a GitHub personal access token with the following scopes:
- `repo` - Full control of private repositories
- `workflow` - Update GitHub Action workflows

Follow these steps to create a token:
1. Go to GitHub Settings → Developer Settings → Personal Access Tokens → Tokens (classic)
2. Generate a new token with the required scopes
3. Copy the token and paste it into the application when prompted

## Technology Stack

- **Frontend**: React, TypeScript, Tailwind CSS
- **Routing**: React Router
- **Styling**: Tailwind CSS with dark mode support
- **API Integration**: Axios for GitHub API requests

## Development

### Project Structure

```
trajectory-visualizer/
│   ├── public/
│   ├── src/
│   │   ├── components/
│   │   ├── services/
│   │   ├── types/
│   │   └── App.tsx
│   ├── package.json
│   └── tsconfig.json
└── README.md
```

### Available Scripts

- `npm start`: Start development server
- `npm build`: Build production-ready app
- `npm test`: Run tests
- `npm eject`: Eject from Create React App

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Acknowledgments
- GitHub for their comprehensive API
