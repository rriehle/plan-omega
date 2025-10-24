# Plan Ω: Family Maritime Survival Manual

A guide for living aboard a sailing vessel to prepare for and survive various civilization collapse scenarios.

## About

This manual provides detailed guidance for achieving complete autonomy and self-sufficiency in a maritime environment, addressing:

- **Economic Collapse** - Mass unemployment, currency failure, supply chain breakdown
- **Civil Unrest** - Widespread violence, government instability, social breakdown
- **Climate Collapse** - Extreme weather, sea level rise, ecosystem failure
- **War** - Regional or global conflict, breakdown of international order

## Documentation

**Live Documentation:** <https://rriehle.github.io/plan-omega/>

The documentation is built with [MkDocs](https://www.mkdocs.org/) using the [Material theme](https://squidfunk.github.io/mkdocs-material/).

## Local Development

### Prerequisites

- Python 3.13+
- pip

### Setup

1. Clone the repository:

```bash
git clone https://github.com/rriehle/plan-omega.git
cd plan-omega
```

2. Activate a Python virtual environment; here we use pyenv:

```bash
pyenv activate py3.13.9-mkdocs
```

3. Install dependencies:

```bash
pip install -r requirements.txt
```

### Working with the Documentation

**Serve locally (with live reload):**

```bash
mkdocs serve
```

Open <http://127.0.0.1:8000> in your browser.

**Build the site:**

```bash
mkdocs build
```

The static site will be generated in the `site/` directory.

**Deploy to GitHub Pages manually:**

```bash
mkdocs gh-deploy
```

## Automatic Deployment

The site automatically deploys to GitHub Pages when you push to the `main` branch via GitHub Actions.

### GitHub Pages Setup

To enable GitHub Pages for your repository:

1. Go to your repository on GitHub
2. Navigate to **Settings** → **Pages**
3. Under **Source**, select **GitHub Actions**
4. The workflow will automatically build and deploy on every push to `main`

The workflow file is located at `.github/workflows/deploy-docs.yml`.

## Framework Principles

### P.A.C.E. Planning

Every critical system has four levels of redundancy:

- **Primary** - Main, most efficient solution
- **Alternate** - Secondary method when primary is unavailable
- **Contingency** - Backup when both primary and alternate fail
- **Emergency** - Last-resort solution using minimal resources

### Threat Levels

- **Level 1: Monitoring** - Normal operations with enhanced preparedness
- **Level 2: Enhanced Readiness** - Early warning signs detected
- **Level 3: Activation** - Imminent threat, execute departure protocols
- **Level 4: Survival Mode** - Long-term autonomy, minimal external contact

## License

**Documentation Content:** [CC BY-SA 4.0](https://creativecommons.org/licenses/by-sa/4.0/)

You are free to:

- **Share** - Copy and redistribute the material
- **Adapt** - Remix, transform, and build upon the material

Under the following terms:

- **Attribution** - Give appropriate credit
- **ShareAlike** - Distribute contributions under the same license

## Contributing

Contributions are welcome! Please feel free to submit issues or pull requests.

---

The best survival plan is one you practice regularly. Knowledge without skills is useless. Skills without practice fade.

**Fair winds and following seas.**
