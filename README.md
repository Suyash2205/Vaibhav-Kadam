# Vaibhav Kadam – Portfolio

Static portfolio site. Deploy to Vercel with the steps below.

## Deploy on Vercel

### Option A: Deploy with Vercel CLI

1. **Install Vercel CLI** (one time):
   ```bash
   npm i -g vercel
   ```

2. **From this folder, log in and deploy**:
   ```bash
   cd /Users/suyash/Vaibhav
   vercel
   ```
   - First run: log in with your Vercel account (browser or token).
   - Follow prompts: link to existing project or create new one.
   - You’ll get a URL like `https://your-project.vercel.app`.

3. **Production deploy**:
   ```bash
   vercel --prod
   ```

### Option B: Deploy with Git (GitHub / GitLab / Bitbucket)

1. Push this project to a Git repo (e.g. GitHub).

2. Go to [vercel.com](https://vercel.com) → **Add New** → **Project**.

3. Import the repo. Vercel will detect it as a static site (no build step).

4. Click **Deploy**. Future pushes to the main branch will auto-deploy.

---

**Project setup:** `vercel.json`, `package.json`, and `.vercelignore` are already configured for static deployment.
