# My Portfolio

Personal portfolio website built with [Hugo](https://gohugo.io/) using the [Congo](https://jpanther.github.io/congo/) theme.

🔗 [View Live Site](https://my-portfolio-14o.pages.dev/)

---

## 🚀 Local Development

To run the site locally and preview your changes in real-time, follow these steps:

1. **Install Hugo** (if you haven't already):
   ```bash
   brew install hugo
   ```
2. **Start the local server**:
   ```bash
   hugo server
   ```
   *To include draft posts or content with future dates, use:*
   ```bash
   hugo server -D
   ```
3. **Open the site**:
   Go to [http://localhost:1313](http://localhost:1313) in your web browser. The server has hot-reloading enabled, so your browser will refresh automatically when you save changes.

---

## ☁️ Hosting and Deployment

- **Hosting Platform**: This site is hosted on **Cloudflare Pages**.
- **Continuous Deployment (CI/CD)**: Cloudflare Pages is connected to this GitHub repository. Whenever you commit and push changes to the `main` branch, Cloudflare Pages will automatically pull the updates, build the static site using Hugo, and deploy them to the live site.