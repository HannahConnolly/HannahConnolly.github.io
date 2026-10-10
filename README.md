# hannahconnolly.dev

Source for my portfolio site, live at **https://hannahconnolly.dev/**.

It's a single static page with no build step or dependencies:

- `index.html` holds all the content and a few lines of inline JavaScript for the light/dark theme toggle
- `styles.css` holds all the styling, including both color themes and the mobile layout

## Running locally

Open `index.html` in a browser. To serve it over HTTP instead:

```sh
python3 -m http.server 8000
```

Then visit http://localhost:8000.

## Deploying

The site is hosted on GitHub Pages and publishes from the `main` branch. The `CNAME` file sets the custom domain; DNS is managed in Cloudflare. Pushing to `main` updates the live site within about a minute.

## Contact

- Email: hannahconnolly949@gmail.com
- GitHub: [HannahConnolly](https://github.com/HannahConnolly)
- LinkedIn: [hannahconn](https://www.linkedin.com/in/hannahconn)
