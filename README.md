[README.md](https://github.com/user-attachments/files/26925983/README.md)
# HTL Skill Tree Web App

A web-based, data-driven visualization tool that displays educational competencies as an interactive skill tree.
In this project, AI was used in certain parts of the development process to save time and support learning. It helped with tasks such as generating code ideas, structuring components, and improving documentation. The use of AI allowed for faster problem-solving and a better understanding of new concepts, while still requiring manual adjustments and critical thinking to ensure the final implementation was correct and meaningful.

## Features

- Configuration-driven architecture using JSON
- Automatic DAG layout with Dagre
- Interactive nodes with hover tooltips
- Click to view detailed sidebar with Markdown content and YouTube embeds
- Support for multiple trees and disconnected sub-graphs

## Getting Started

1. Install dependencies: `npm install`
2. Start the development server: `npm run dev`
3. Open http://localhost:5173 in your browser

## Configuration

Edit `src/config/skills.json` to add or modify skills.

## Tech Stack

- React
- React Flow
- Dagre
- Marked
- Vite
