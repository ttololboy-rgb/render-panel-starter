# Render Panel Starter

Starter dashboard only; it does not include VPS controls or server-management privileges.

## Deploy
1. Create a new GitHub repository named `render-panel-starter`.
2. Upload all files/folders from this ZIP to the repository root.
3. In Render, choose **New + → Blueprint** and connect that repository, or create a Web Service with:
   - Runtime: Node
   - Build command: `npm install`
   - Start command: `npm start`
   - Plan: Free

The free service may sleep when inactive. Do not add secrets or API keys to public source files.
