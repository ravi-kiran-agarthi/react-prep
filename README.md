# react-prep

Handy senior React frontend prep: performance playbook, daily katas, 12-week plan, and a progress tracker (saved in your browser).

Site: https://ravi-kiran-agarthi.github.io/react-prep/

Single static `index.html`, no dependencies, no build step, light/dark/system theme. Progress is stored in `localStorage`.

## Updates

Each deploy stamps the commit SHA into `index.html` and `version.json`. The page checks it every 5 min and on tab focus, and shows "New version available" when it differs.
