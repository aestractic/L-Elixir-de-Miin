# L'Élixir de Miin

A modern, elegant website for L'Élixir de Miin wellness services, built with Astro and TailwindCSS.

## 🌟 Features

- Responsive modern design with dark theme
- Interactive appointment scheduling system
- WhatsApp integration for direct communication
- Spanish language support
- Dynamic calendar component
- Treatment services showcase
- Philosophy and brand story section

## 🛠️ Tech Stack

- [Astro](https://astro.build/) - Static Site Generator
- [TailwindCSS](https://tailwindcss.com/) - Styling
- [date-fns](https://date-fns.org/) - Date manipulation and formatting
- Vanilla JavaScript for interactivity

## 🚀 Getting Started

### Prerequisites

- [Bun](https://bun.sh/) package manager
- Node.js 18 or higher

### Installation

1. Clone the repository:
```bash
git clone [your-repo-url]
cd L-Elixir-de-Miin
```

2. Install dependencies:
```bash
bun install
```

3. Start the development server:
```bash
bun dev
```

The site will be available at `http://localhost:4321`

## 📁 Project Structure

```text
/
├── public/          # Static assets
├── src/
│   ├── components/  # UI components
│   │   ├── Calendar.astro
│   │   ├── Footer.astro
│   │   ├── Header.astro
│   │   ├── Hero.astro
│   │   ├── Philosophy.astro
│   │   ├── Schedule.astro
│   │   └── Treatments.astro
│   ├── layouts/     # Page layouts
│   │   └── Layout.astro
│   ├── pages/       # Route pages
│   │   └── index.astro
│   └── styles/      # Global styles
│       └── global.css
└── package.json
```

## 🔧 Available Commands

| Command        | Action                                           |
| :------------- | :----------------------------------------------- |
| `bun install`  | Installs dependencies                            |
| `bun dev`      | Starts local dev server at `localhost:4321`      |
| `bun build`    | Build your production site to `./dist/`          |
| `bun preview`  | Preview your build locally, before deploying     |

## 🎨 Color Scheme

- Primary: [Your primary color]
- Dark Background: #0A0A0B
- Light Text: #E8E8E8
- Muted Text: [Your muted text color]
- Border Dark: [Your border color]

## 📱 WhatsApp Integration

The website includes direct WhatsApp integration for appointment scheduling. The contact button connects to the business WhatsApp number with a pre-formatted message.

## 🌐 Deployment

[Add your deployment instructions here]

## 📄 License

[Add your license information here]

## 👥 Contact

[Add your contact information here]

```sh
bun create astro@latest -- --template basics
```

[![Open in StackBlitz](https://developer.stackblitz.com/img/open_in_stackblitz.svg)](https://stackblitz.com/github/withastro/astro/tree/latest/examples/basics)
[![Open with CodeSandbox](https://assets.codesandbox.io/github/button-edit-lime.svg)](https://codesandbox.io/p/sandbox/github/withastro/astro/tree/latest/examples/basics)
[![Open in GitHub Codespaces](https://github.com/codespaces/badge.svg)](https://codespaces.new/withastro/astro?devcontainer_path=.devcontainer/basics/devcontainer.json)

> 🧑‍🚀 **Seasoned astronaut?** Delete this file. Have fun!

![just-the-basics](https://github.com/withastro/astro/assets/2244813/a0a5533c-a856-4198-8470-2d67b1d7c554)

## 🚀 Project Structure

Inside of your Astro project, you'll see the following folders and files:

```text
/
├── public/
│   └── favicon.svg
├── src/
│   ├── layouts/
│   │   └── Layout.astro
│   └── pages/
│       └── index.astro
└── package.json
```

To learn more about the folder structure of an Astro project, refer to [our guide on project structure](https://docs.astro.build/en/basics/project-structure/).

## 🧞 Commands

All commands are run from the root of the project, from a terminal:

| Command                   | Action                                           |
| :------------------------ | :----------------------------------------------- |
| `bun install`             | Installs dependencies                            |
| `bun dev`             | Starts local dev server at `localhost:4321`      |
| `bun build`           | Build your production site to `./dist/`          |
| `bun preview`         | Preview your build locally, before deploying     |
| `bun astro ...`       | Run CLI commands like `astro add`, `astro check` |
| `bun astro -- --help` | Get help using the Astro CLI                     |

## 👀 Want to learn more?

Feel free to check [our documentation](https://docs.astro.build) or jump into our [Discord server](https://astro.build/chat).
