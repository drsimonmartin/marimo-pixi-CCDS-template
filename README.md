# marimo + pixi Starter Template

A starter template for [marimo](https://marimo.io) notebooks using [pixi](https://github.com/prefix-dev/pixi) for dependency and project management. This template provides a modern Python development setup with a folder structure inspired by the [Cookie Cutter Data Science](https://cookiecutter-data-science.drivendata.org) project. The original template is here: https://github.com/marimo-team/marimo-pixi-starter-template

## Features

- 🚀 Python 3.12+ support
- 📦 Fast dependency management with `pixi`
- 🧪 Testing setup with pytest
- 🎯 Code quality with Ruff (linting + formatting)
- 👷 CI/CD with GitHub Actions
- 📓 Interactive notebook development with marimo

## Prerequisites

- [pixi](https://github.com/prefix-dev/pixi) installed

## Getting Started

1. Clone this repository:

   ```bash
   git clone https://github.com/yourusername/marimo-pixi-CCDS-template
   cd marimo-pixi-starter-template
   ```

2. Run the marimo editor:

   ```bash
   pixi run edit
   ```

## Development

### Running Tests

```bash
pixi run test
```

### Linting and formatting

```bash
pixi run lint
pixi run format
```

### Install pre-commit

```bash
pixi run pre-commit-install
```

## Project Structure

```markdown
├── .github/          # GitHub Actions workflows
├── marimo-notebooks/              # Source code
│   └── app.py        # Sample marimo notebook
└── data/         # Data used in the work
│        └── raw/        		# the raw data - do not change
│        └── processed/        	# the final data for modelling
│        └── interim/        	# intermediate data - has been transformed
│        └── external/	        # any data from 3rd parties
├── docs/              # documentation for code etc. Suggest use mkdocs format
├── references/              	# Any papers, manuals etc used
├── reports/              # Any output reports (LaTeX, Markdown, Jupyterbooks, Quarto, etc.)
│        └── figures/        	# figures, graphs, etc for reports
├── tests/            # Test files
├── pyproject.toml    # Project configuration
└── pixi.lock         # Dependency lock file

```

## License

MIT
