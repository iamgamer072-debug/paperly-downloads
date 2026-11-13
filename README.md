# paperly-downloads
Downloads for Paperly: the installers the online Paperly Setup fetches (release `apps`).

## Uptime check
`.github/workflows/uptime.yml` checks every 5 minutes, from GitHub (outside Cloudflare):
- the Sheets, Docs, download and admin sites
- the accounts server
- the setup app list

If something is down, it opens an issue named **Paperly is down**, assigned to the owner, so GitHub emails them. It closes the issue by itself when everything answers again.
