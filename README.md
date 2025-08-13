# Zen Onboarding 90-Day Plan

A culturally respectful, structured 90-day phased introduction to foundational Zen-inspired practice with sustainable habit formation.

## 🌐 Live Site

Visit the live documentation at: [https://sfboss.github.io/generated_plan_zen_ease_into_plan/](https://sfboss.github.io/generated_plan_zen_ease_into_plan/)

## 🚀 Deployment

This site is automatically deployed to GitHub Pages using GitHub Actions whenever changes are pushed to the `main` branch.

### Local Development

1. Install Python dependencies:

    ```bash
    pip install -r requirements.txt
    ```

2. Serve the site locally:

    ```bash
    mkdocs serve
    ```

3. Build the site:
    ```bash
    mkdocs build
    ```

### GitHub Pages Setup

The site is configured for automatic deployment via GitHub Actions:

1. **GitHub Actions Workflow**: `.github/workflows/static.yml` handles the build and deployment
2. **MkDocs Configuration**: `mkdocs.yml` contains all site settings
3. **Dependencies**: `requirements.txt` lists all Python packages needed

The workflow automatically:

-   Installs Python and dependencies
-   Builds the MkDocs site
-   Deploys to GitHub Pages

## 📁 Project Structure

```
docs/                    # Documentation source files
├── index.md            # Homepage
├── getting-started/    # Introduction materials
├── foundations/        # Core practice information
├── plan/              # 90-day plan phases
├── days/              # Daily practice pages
├── reflection/        # Review and journaling
├── enrichment/        # Additional resources
├── meta/              # Project metadata
└── stylesheets/       # Custom CSS

mkdocs.yml              # MkDocs configuration
requirements.txt        # Python dependencies
.github/workflows/      # GitHub Actions deployment
```

## 🛠️ Technical Details

-   **Framework**: MkDocs with Material theme
-   **Hosting**: GitHub Pages
-   **CI/CD**: GitHub Actions
-   **Python**: 3.x with Material for MkDocs extensions

## 📝 Contributing

1. Fork the repository
2. Make your changes in the `docs/` directory
3. Test locally with `mkdocs serve`
4. Submit a pull request

Changes will be automatically deployed once merged to the main branch.
