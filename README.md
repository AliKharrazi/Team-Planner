# STP Planning Suite

Interactive planning tools for the Sub-Transmission Planning team at AusNet Services.

## Tools

### 📋 CY26 Roadmap Planner
Calendar-year roadmap with Gantt chart, Kanban board, and list views. Track initiatives across BAU, continuation, and new projects with milestones, subtasks, and team assignments.

### 📅 Weekly Workload Planner  
Rolling 4-week view showing who is doing what each day. Balance workload across team members with capacity indicators, track tasks, meetings, and leave.

## Deployment (GitHub Pages)

1. Create a new repository on GitHub (e.g. `stp-planner`)
2. Upload all files: `index.html`, `roadmap.html`, `weekly.html`, `README.md`
3. Go to **Settings → Pages → Source: Deploy from a branch → Branch: main → / (root) → Save**
4. Wait 1–2 minutes — your suite is live at `https://<username>.github.io/stp-planner/`

## Cloud Sync

Both tools support shared cloud sync via GitHub Gists (each tool uses its own Gist):

1. Generate a GitHub Personal Access Token with `gist` scope
2. In each tool, click **☁ Sync → Create New & Push**
3. Share the Gist ID with your team — they enter it + their own token to connect
4. Changes auto-sync every 60 seconds

## Local Use

All tools work fully offline. Open any HTML file in a browser — data saves to localStorage. Use Export/Import for backup.
