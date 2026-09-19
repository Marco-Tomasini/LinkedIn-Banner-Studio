# LinkedIn Banner Studio

<p align="left">
  <b>English</b> •
  <a href="README.pt-BR.md">Português</a>
</p>

---

Visual banner generator for LinkedIn, designed for tech profiles. The project is a static page: enter your details, choose a template, and export a PNG in the recommended LinkedIn size (`1584 × 396 px`).

## Features

- Six banner composition templates.
- Four ready-to-use color presets and a custom palette with configurable background, accent, and text colors.
- Customizable name, title/role, institution, and technologies.
- Logos via file upload or URL for the institution and each technology, with individual scale adjustments from `50%` to `300%` next to the preview.
- Badge option featuring enlarged logos.
- Optional overlay guide indicating the area covered by the LinkedIn profile photo.
- Fullscreen preview with zoom, pinch, pan, and fit-to-screen controls.
- Responsive layout adapted for mobile and desktop screens.
- Direct PNG export from `1×` up to `5×` (up to `7920 × 1980 px`).

## How to Use

1. Open [index.html](index.html) in a modern web browser.
2. Enter your name, subtitle/title, institution, and technologies.
3. Select a color theme and a composition layout.
4. Optionally, upload logos or provide public image URLs.
5. Choose the export scale from `1×` to `5×` and click **Download PNG**.

`1×` generates the recommended LinkedIn dimensions (`1584 × 396 px`). Higher scales redraw the banner at high resolutions; they are useful for archiving a master copy or editing in graphic software.

To assign custom categories to technologies, separate them using `|`:

```text
PHP | Backend, JavaScript | Frontend, SQL | Database
```

## Fullscreen on Mobile

In fullscreen mode, the banner opens enlarged on portrait devices for easier readability. Use the `−` and `+` buttons, pinch gestures, and drag controls to pan. The **Fit** button resets the view to display the complete banner.

## Technologies

- Pure HTML, CSS, and JavaScript.
- [Tailwind CSS](https://tailwindcss.com/) via CDN.
- [Font Awesome](https://fontawesome.com/) and Google Fonts via CDN.

No package installation or server runtime is required to use the project.

## Deployment to GitHub Pages

The project's entry file is `index.html`, which is automatically recognized by GitHub Pages.

The repository includes a workflow in [`.github/workflows/static.yml`](.github/workflows/static.yml): upon pushing to the `main` branch, it deploys the updated version via GitHub Actions.

The project is published at:

[https://marco-tomasini.github.io/LinkedIn-Banner-Studio/](https://marco-tomasini.github.io/LinkedIn-Banner-Studio/)

For new forks or copies of the project, navigate to **Settings → Pages** in your repository and select **GitHub Actions** as the deployment source. Once the workflow completes, the site will be live at your corresponding user and repository URL.

## License

This project is licensed under the [MIT License](LICENSE).

## Credits

- Initial base project: [Isabela de Oliveira](https://github.com/isabela728).
- Subsequent evolutions, features, and enhancements: [Marco Tomasini](https://github.com/marco-tomasini).
