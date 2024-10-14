# LinkedIn AI Reply Chrome Extension

https://github.com/user-attachments/assets/5abc4bd9-e15d-40bf-843d-2b80ce4caa2e

This project is a Chrome extension designed to assist users on LinkedIn by generating replies to messages. The extension does not use an actual API but simulates a response generation, making it a demo extension.

## Overview

This Chrome extension allows users to:

1. Focus on a LinkedIn message input field to reveal an AI icon.
2. Click the AI icon to open a modal where they can input a command.
3. Clicking the "Generate" button in the modal inserts a static, pre-defined reply in the message input field.

## Tech Stack

- **Framework**: [WXT Framework](https://wxt.dev/)
- **Languages**: React, TypeScript, Tailwind CSS
- **Chrome Extension Version**: Manifest v3

## Features

- **AI Icon Visibility**: The AI icon appears when the LinkedIn message input field is focused and disappears when the focus is removed.
- **Modal for AI Reply**: Clicking the AI icon opens a modal, allowing users to input any command.
- **Static Response Generation**: When the "Generate" button is clicked, a static text (`Thank you for the opportunity! If you have any more questions or if there's anything else I can help you with, feel free to ask.`) is inserted into the message input field.
- **Insert into LinkedIn**: The static response is inserted directly into the LinkedIn message input field.

## Folder Structure

````bash
linkedin-ai-reply/
├── assets/
│   └── react.svg
├── entrypoints/
│   ├── popup/
│   │   ├── App.css
│   │   ├── App.tsx
│   │   ├── index.html
│   │   ├── main.tsx
│   │   └── style.css
│   ├── background.ts
│   └── content.ts
├── public/
│   ├── icon/
│   │   ├── 16.png
│   │   ├── 32.png
│   │   ├── 48.png
│   │   ├── 96.png
│   │   └── 128.png
│   └── wxt.svg
├── .gitignore
├── package-lock.json
├── package.json
├── README.md
├── tsconfig.json
└── wxt.config.ts
````

## Getting Started

### Prerequisites

Make sure you have the following installed on your local machine:

- **Node.js**: >=14.x
- **npm**: >=6.x
- **Chrome Browser**: For loading and testing the extension.

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/hzratali/linkedin-ai-reply.git
   cd linkedin-ai-reply

2. Navigate to the project directory:

   ```bash
   cd linkedin-ai-reply

3. Install the dependencies:

   ```bash
   npm install

4. Build the extension:

   ```bash
   npm run build


## Usage

1. Open chrome://extensions/ in your Chrome browser.

2. Enable Developer mode (toggle in the top right corner).

3. Click on Load unpacked and select the .output/chrome-mv3 directory from the project folder.

4. The extension will be added to your Chrome browser.


## Built With

1. WXT - A framework for building web extensions.

2. React - Frontend framework used for UI development.

3. TypeScript - A typed superset of JavaScript that adds static types.

4. Tailwind CSS - A utility-first CSS framework for styling.
