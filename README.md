# JavaScript Learning Projects

This repository is a collection of small, browser-based JavaScript exercises and applications. It documents progression from DOM and language fundamentals to interactive interfaces, object-oriented examples, and API-driven applications.

## Why this repository is useful

- Provides focused examples of vanilla JavaScript, HTML, and CSS.
- Demonstrates DOM queries, events, forms, arrays, classes, maps, local storage, and browser APIs.
- Includes complete mini-applications that can be opened and modified without a framework or build system.
- Offers a practical reference for experimenting with frontend concepts in isolation.

## Projects

| Directory | What it demonstrates |
| --- | --- |
| [`ArrayMethods/`](ArrayMethods/) | Interactive array operations such as adding, removing, sorting, and reversing values |
| [`Banking/`](Banking/) | Account and transaction concepts using JavaScript classes |
| [`BasicCalculator/`](BasicCalculator/) | Calculator operations, validation, clearing, and keyboard shortcuts |
| [`Dark Mode/`](Dark%20Mode/) | Theme switching with `localStorage` |
| [`Element Query/`](Element%20Query/) | Reusable helpers for querying, creating, and updating DOM elements |
| [`FirstCode/`](FirstCode/) | Introductory JavaScript examples, syntax exercises, and a small library example |
| [`Game Test/`](Game%20Test/) | Early game-state and browser interaction experiments |
| [`InteractiveImageGallery/`](InteractiveImageGallery/) | Add and display images dynamically |
| [`Math Assignment/`](Math%20Assignment/) | Basic math calculations and user input handling |
| [`PokemonAPI/`](PokemonAPI/) | Search, compare, and analyze Pokémon using [PokéAPI](https://pokeapi.co/) |
| [`Task Scheduler/`](Task%20Scheduler/) | Task scheduling and interactive state updates |
| [`ToDoList/`](ToDoList/) | Add, complete, and remove tasks |
| [`UpgradedBankingApp/`](UpgradedBankingApp/) | A more complete banking interface with login, account creation, and transactions |

## Getting started

### Prerequisites

- A modern web browser
- Git, if you want to clone the repository
- A local HTTP server for projects that use modules or browser features that are restricted from `file://` pages

### Run a project

```bash
git clone https://github.com/VoidLance/JavaScript.git
cd JavaScript
```

Open a project's `index.html` directly in a browser, for example:

```text
PokemonAPI/index.html
```

For a more reliable local setup, serve the repository with any static HTTP server. For example, if Python is installed:

```bash
python3 -m http.server 8000
```

Then visit `http://localhost:8000/` and open the project directory you want to explore.

### Pokémon Finder development notes

[`PokemonAPI/`](PokemonAPI/) is a standalone static application. It loads Tailwind CSS from a CDN and retrieves data from PokéAPI, so it requires an internet connection. Its detailed feature and development notes are in [`PokemonAPI/README.md`](PokemonAPI/README.md).

## Usage examples

Each project is self-contained:

1. Open its `index.html`.
2. Use the controls in the page.
3. Inspect the corresponding JavaScript file to see how the behavior is implemented.
4. Edit the HTML, CSS, or JavaScript and refresh the browser to try an idea.

For example, open [`ToDoList/index.html`](ToDoList/index.html) to try task management, or [`BasicCalculator/index.html`](BasicCalculator/index.html) to explore event handling and input-driven calculations.

## Project layout

Most projects follow this structure:

```text
ProjectName/
├── index.html   # Page markup and controls
├── script.js    # Application behavior
└── styles.css   # Optional project-specific styles
```

Some examples use different filenames or nested folders; read the local files in that project for its entry points.

## Support and documentation

- Start with the README or notes inside the project directory you are using.
- For the Pokémon application, see [`PokemonAPI/QUICK-REFERENCE.md`](PokemonAPI/QUICK-REFERENCE.md).
- For API behavior, consult the [PokéAPI documentation](https://pokeapi.co/docs/v2).
- To report a reproducible problem or request an improvement, open an issue in the [GitHub repository](https://github.com/VoidLance/JavaScript/issues).

## Contributing

Contributions and learning-focused improvements are welcome. To contribute:

1. Create a branch from the current default branch.
2. Make a focused change in the relevant project directory.
3. Test the page manually in a modern browser.
4. Describe the change and verification steps in your pull request.

Please keep examples dependency-light, preserve the self-contained nature of each project, and update local documentation when behavior changes.

## Maintainer

Maintained by [VoidLance](https://github.com/VoidLance). See the repository's [MIT License](LICENSE) for licensing information.
