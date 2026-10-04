# AI GMD Creator

GitHub Pages-ready iPad web app for generating Geometry Dash level blueprints and downloading `.gmd` files.

## Publish on GitHub Pages

1. Create a repository named `AI-GMD-Creator`.
2. Upload `index.html`.
3. Go to **Settings → Pages**.
4. Under **Build and deployment**, choose **Deploy from a branch**.
5. Select `main` and `/ (root)`, then Save.
6. After deployment, open:

`https://urfellowbacon.github.io/AI-GMD-Creator/`

## Notes

The AI mode calls the OpenAI Responses API directly from the browser, so an API key entered into the page is exposed to that browser session. Do not put a personal production API key into a public website.

The GMD writer is a lightweight prototype and uses a deliberately simplified object representation; it is not a guarantee of compatibility with every Geometry Dash version.
