# Wärmenetz Baudenbach

[![Built with Zensical](https://img.shields.io/badge/Built_with-Zensical-526CFE?style=for-the-badge)](https://zensical.io)

**Website:** https://www.waermenetz-baudenbach.de

The website is automatically generated and deployed whenever changes are made to the [`docs`](./docs) directory.

## How it works

> **Note:** This project uses **Zensical**, the successor to MkDocs.

Zensical generates a static website from the Markdown files located in the [`docs`](./docs) directory.

Every change pushed to the `main` branch automatically triggers the build and deployment process, ensuring the website is always up to date.

Project-specific configuration is managed through the Zensical configuration files included in this repository.

## Local development

1. Install Python.
2. Clone this repository.
3. Install the project dependencies:

   ```bash
   pip install --upgrade -r requirements.txt
   ```

4. Start the local development server:

   ```bash
   zensical serve
   ```

5. Open your browser and navigate to:

   ```
   http://localhost:8000/
   ```

6. Any changes to the documentation are automatically detected, and the browser reloads instantly.

## Updating your local installation

Whenever the project dependencies change, update your local environment by running:

```bash
pip install --upgrade -r requirements.txt
```
