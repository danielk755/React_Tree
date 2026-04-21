[README.md](https://github.com/user-attachments/files/26925983/README.md)
# HTL Skill Tree Web App

A web-based, data-driven visualization tool that displays educational competencies as an interactive skill tree.

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
