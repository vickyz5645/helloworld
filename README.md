# helloworld.vigneshvc.space

A simple, modern static "Hello World" site designed for deployment on **Cloudflare Pages** (Free Tier).

## 🌐 Live URL
- Custom Subdomain: [https://helloworld.vigneshvc.space](https://helloworld.vigneshvc.space)
- Root Domain: [https://vigneshvc.space](https://vigneshvc.space)

## 🚀 Cloudflare Pages Setup

1. Log in to the [Cloudflare Dashboard](https://dash.cloudflare.com/).
2. Navigate to **Workers & Pages** -> **Create application** -> **Pages** -> **Connect to Git**.
3. Select this repository: `vickyz5645/helloworld`.
4. Set Build Settings:
   - **Framework preset:** `None`
   - **Build command:** *(leave empty)*
   - **Build output directory:** `/` (or root)
5. Click **Save and Deploy**.
6. Once deployed, navigate to **Custom domains** tab in your Pages project, click **Set up a custom domain**, and enter:
   `helloworld.vigneshvc.space`.
   Cloudflare will automatically link the DNS record to your Pages deployment!
