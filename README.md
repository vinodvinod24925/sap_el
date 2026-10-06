# FlinkGuard

A real-time ad click fraud detection dashboard built with React + Vite, simulating a streaming fraud-monitoring pipeline inspired by Apache Flink, Kafka, and ML-driven risk scoring.

## Overview

This project presents a modern monitoring UI for a fraud detection system that tracks:

- real-time ad click events
- Kafka consumer lag
- Flink engine state
- fraud rule evaluation
- ML training and model metrics
- attack simulation and defense workflows
- exported forensic report generation

## Tech Stack

- React 19
- TypeScript
- Vite
- Tailwind CSS
- Lucide icons
- Custom streaming simulation service

## Project Structure

```text
.
├── src/
│   ├── App.tsx
│   ├── components/
│   ├── data/
│   ├── services/
│   ├── types/
│   └── index.css
├── data/
├── models/
├── package.json
├── vite.config.ts
├── tsconfig.json
├── train_talkingdata_model.py
├── requirements-ml.txt
└── README.md
```

## Features

- Dashboard overview with live streaming metrics
- Workflow view describing the fraud detection pipeline
- ML training view with model insights
- Code artifacts view for the implementation details
- Attack lab for simulated malicious scenarios
- Viva defense workflow for protective measures
- Event drill-down modal for detailed click inspection
- Export report modal for generated documentation

## Getting Started

### Prerequisites

- Node.js 18+
- npm

### Install dependencies

```bash
npm install
```

### Run the app locally

```bash
npm run dev
```

The app will be available at:

```text
http://localhost:3000/
```

### Build for production

```bash
npm run build
```

## Notes

This repository includes a simulated dashboard and data model for presentation/demo purposes, with a fraud detection narrative built around Apache Flink + Kafka + ML workflows.

## License

This project is provided for educational and demonstration purposes.
