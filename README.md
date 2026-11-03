# Social Slingshot: website

The public pages for [Social Slingshot](https://rifle-ak.is-a-better.dev/social-slingshot-site/), a self-hosted creator analytics dashboard. They're published with GitHub Pages from the root of `main`.

- `index.html`: home page
- `terms.html`, `privacy.html`: Terms of Service and Privacy Policy
- `tiktok/callback/`: TikTok Login Kit redirect page. TikTok requires an `https` redirect URI, but Slingshot runs locally over `http`. This page forwards only `code`, `state`, `scopes`, `error` and `error_description` to `http://127.0.0.1:8000/connect/tiktok/callback`, and stores nothing.
- `assets/icon-1024.png`: the app icon (1024×1024)

TikTok URL-prefix verification files go in the root of this repo.
