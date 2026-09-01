# AI Media Workflow Engine

An end-to-end automated media processing pipeline that ingests audio/video files, extracts metadata, generates AI-powered transcripts, and routes automated workflows via scalable API pipelines.

## System Architecture
`Client / Upload` -> `Node.js API Server` -> `FFmpeg Metadata Extractor` -> `Gemini AI Engine` -> `PostgreSQL DB`

## Core Features
* **Automated Media Ingestion:** Ingests raw audio and video files via REST API endpoints.
* **Metadata & Audio Extraction:** Extracts duration, codecs, and strips audio streams using FFmpeg.
* **AI Processing Pipeline:** Sends audio snippets to Gemini API for dynamic transcription and summarization.
* **Structured Logs & Storage:** Persists processing states and structured JSON metadata in PostgreSQL.

## Tech Stack
* **Language/Runtime:** Node.js, JavaScript
* **Core Libraries:** Express, `@google/genai`
* **Database & Caching:** PostgreSQL, Redis
* **DevOps/Tools:** Docker, Git, VS Code

## Getting Started
Instructions for local setup will be documented as core modules are implemented.
