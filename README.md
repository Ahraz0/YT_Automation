# n8n YouTube Automation

This workflow automatically uploads any new video placed in a Google Drive folder to YouTube.

## Workflow Steps
1. **Drive Trigger** → Watches for new files in a specific Google Drive folder.  
2. **Drive Download File** → Downloads the file as binary.  
3. **YouTube Upload Video** → Uploads the video to your YouTube channel.  

## Export
The workflow is provided as `youtube-drive-upload.json`.  
You can import it directly into n8n.

---

⚡ Tech: n8n, Google Drive API, YouTube API
