# Re_designui-ux_drdo
Dashboard UI Redesign

A React + Vite frontend UI project.

Quick Start

Requirements

Install Node.js LTS and VS Code.

Check Node.js:

node -v
npm -v

Open the Correct Folder

Open the main project folder in VS Code:

Dashboard__ui_redesign

Do NOT open only the src folder.

The project root should contain:

Dashboard__ui_redesign/
├── package.json
├── index.html
├── vite.config.ts
├── postcss.config.mjs
├── src/
│   └── main.tsx
└── guidelines/

The terminal must be inside:

...\Dashboard__ui_redesign>

NOT:

...\Dashboard__ui_redesign\src>

Install Dependencies

Open Terminal → New Terminal in VS Code and run:

npm install

Wait for it to finish.

Run the UI

Run:

npm run dev

Vite should display a URL similar to:

Local: http://localhost:5173/

Open that URL in your browser.

Windows Command Sequence

If the project is inside Downloads:

cd "C:\Users\praka\Downloads\Dashboard__ui_redesign"
npm install
npm run dev

Replace praka with your Windows username if needed.

Common Error: main.tsx Not Found

If you see:

[vite] Pre-transform error:
Failed to load url /src/main.tsx
Does the file exist?

Stop Vite:

Ctrl + C

Check the current folder:

pwd

It should end with:

Dashboard__ui_redesign

Check the project root:

dir

You should see:

package.json
index.html
vite.config.ts
src

Then check:

dir src\main.tsx

If it exists, run:

npm run dev

If npm Is Not Recognized

Install Node.js LTS, restart VS Code, open a new terminal, and run:

node -v
npm -v

Run the Project Later

After the first successful installation, normally use:

cd "C:\Users\praka\Downloads\Dashboard__ui_redesign"
npm run dev

You do not need to run npm install every time.

Stop the Server

Press:

Ctrl + C

Production Build

To test a production build:

npm run build

The output will be created in:

dist/

Important Files

File

Purpose

package.json

Dependencies and npm scripts

index.html

Main HTML entry

src/main.tsx

React entry point

src/app/App.tsx

Main application

vite.config.ts

Vite configuration

src/styles/

Project styling

Available Commands

Command

Purpose

npm install

Install dependencies

npm run dev

Start local development server

npm run build

Create production build

Important Rules

Run npm commands from the folder containing package.json.

Do not run npm run dev from inside src.

Do not delete src/main.tsx.

If Vite shows an error, stop it with Ctrl + C before making changes.

Use the exact Local: URL shown by Vite.

Troubleshooting Commands

pwd
dir
dir package.json
dir src\main.tsx
npm install
npm run dev

One-Minute Setup

cd "C:\Users\praka\Downloads\Dashboard__ui_redesign"
npm install
npm run dev

Then open:

http://localhost:5173/
