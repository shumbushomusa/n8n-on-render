# n8n on Render

This repository contains a **Render Blueprint (`render.yaml`)** to deploy [n8n](https://n8n.io/) — a powerful open-source workflow automation tool — on Render.com using the official Docker image.

---

## How to Deploy

### Option 1: Deploy via Render Blueprint

1. Go to [https://dashboard.render.com/blueprint](https://dashboard.render.com/blueprint)
2. Click **"New Blueprint"**
3. Paste the content of the `render.yaml` file from this repo
4. Click **"Apply"**
5. Wait for your n8n service to deploy

---

### Option 2: Deploy from this GitHub Repo

1. Push this repo to your GitHub account
2. On Render dashboard, click **"New Web Service"**
3. Select **"Deploy from GitHub"**
4. Choose this repo
5. Render will detect the `render.yaml` and deploy your n8n instance

---

## Access Your n8n Instance

Once deployed, open:
