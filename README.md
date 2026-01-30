# Dacoam
Dacoam (Database Comic Amin) is my personal project in making an all in one place that I can access comic information, track what issues I have read, and give my reviews on said issues. 

# Purpose
I like journaling and keeping track of the media I have consumed, thus Dacoam focuses on the journalling aspect of comic reading compared to many other comic websites. I plan to build it with a focus on memory safety and systems-level efficiency, it serves as a private, offline-capable alternative to cloud-based collectors. 

As a Computer Science student, this project serves as learning experience for me to dabble in functional programming (Rust), memory management, security, and concurrency.

# Teck Stack (Plan)

Backend: Rust (High-performance systems logic & Memory safety)

Frontend: React + TypeScript (Type-safe UI components)

Database: SQLite (Local-first persistence)

Interface: Tauri 2.0 (Bridging the frontend to native OS APIs)

Styling: Tailwind CSS

# Project Architecture

# Project Roadmap

Phase 1: CRUD Implementation: Establish a basic SQLite connection and handle basic "Create, Read, Update, Delete" operations in Rust.

Phase 2: Asynchronous API Integration: Implementing reqwest in Rust to fetch metadata from the Comic Vine API without blocking the main thread.

Phase 3: Image Management: Managing local file system paths for cover art to optimize performance and storage.

Phase 4: Data Visualization: (Planned) Building a dashboard to visualize reading habits using D3.js or Chart.js

# Setup and Installation

Prerequisites

[All dependies for Tauri 2.0] (https://tauri.app/start/prerequisites/)

Developer Install

1. Clone the repo
`git clone git@github.com:AlAminBristol/Dacoam.git`
`cd Dacoam`

2. Install dependencies
`npm install`

3. Run in develoment mode
`npm run tauri dev`

[If npm cant be run on system](https://dev.to/jackfd120/resolving-npm-execution-policy-error-in-powershell-a-step-by-step-guide-for-developers-32ip)

# Reflections and Journal

# License
