# streamline

streamline is a web application landing page designed to showcase a SaaS productivity platform. The app highlights features, benefits, and calls to action for users interested in optimizing their workflow and boosting efficiency.

## Features
- Modern, responsive landing page design
- Highlights SaaS productivity features and benefits
- Clear calls to action for sign-up or demo
- Engaging visuals and user testimonials
- Contact and support information

## Getting Started

### Prerequisites
- Node.js (version 18 or higher)
- npm

### Installation
1. Clone the repository:
    ```bash
    git clone <repository-url>
    cd <project-directory>
    ```
2. Install dependencies:
    ```bash
    npm install
    ```

### Running the Development Server
To start the development server, run:
```bash
npm run dev
```
This will typically start the server on `http://localhost:3000`.

## Technologies Used
- Vite
- TypeScript
- React
- shadcn-ui
- Tailwind CSS

## Deployment (GitHub Pages)

You can deploy this project to GitHub Pages:

1. Build the static site:
    ```bash
    npm run build
    ```
2. Install the `gh-pages` package if you haven't already:
    ```bash
    npm install --save-dev gh-pages
    ```
3. Add the following to your `package.json`:
    ```json
    "homepage": "https://<your-github-username>.github.io/streamline",
    "scripts": {
      "predeploy": "npm run build",
      "deploy": "gh-pages -d dist"
    }
    ```
4. Deploy:
    ```bash
    npm run deploy
    ```

## Custom Domain
You can connect a custom domain to your deployed project. Refer to your hosting provider's documentation for instructions. 