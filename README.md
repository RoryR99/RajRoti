# Raj Roti website

The deployable website is in [`dist`](dist). It uses plain HTML, CSS, JavaScript, and image assets, so no build command is required.

## Deploy with GitHub Pages

1. Create a GitHub repository and push this project to its `main` branch.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, choose **GitHub Actions** as the source.
4. Run **Deploy Raj Roti to GitHub Pages** from the Actions tab, or push another commit to `main`.

The included workflow publishes only the contents of `dist`, and future pushes to `main` deploy automatically.

The site uses relative asset and page links, so it works from a project URL such as `https://username.github.io/repository-name/` without additional path configuration.
