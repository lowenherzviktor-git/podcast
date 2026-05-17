# Exits & Chaos

Source for the podcast landing page at https://podcast.l1advisory.com/

An L1 Advisory production. Hosts: Viktor Legetsky & Patrick Pilipiec.

## How this deploys

- Single static `index.html`, no build step.
- Auto-deployed by Vercel on push to `main`.
- Vercel project: `exits-and-chaos` (ID `prj_MFsSlMPtv6ZBDGkB6pUuS0WKZZ7B`), scope `lowenherzviktor-gits-projects`, Hobby plan.
- Production domain: `podcast.l1advisory.com` (CNAME to Vercel, Frankfurt region).

## How to edit

1. Pull latest: `git pull`
2. Edit `index.html`.
3. Commit and push: `git add index.html && git commit -m "your message" && git push`
4. Vercel auto-deploys within ~30 seconds. Verify at https://podcast.l1advisory.com/.

## Forms

The Apply and Notify forms POST to n8n webhooks (see inline JS at the bottom of `index.html`).
