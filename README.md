# MemeBot Frontend

Web interface for reviewing and approving meme content before posting.

## Setup

### Configuration

1. Update the API URL in `index.html` line 246 to point to your Railway backend:
   ```javascript
   const API_BASE = 'https://your-railway-app.railway.app';
   ```

### Deploy to Vercel

1. Push this repository to GitHub
2. Import the project in Vercel
3. Deploy (no build steps needed - pure HTML/CSS/JS)

### Features

- Review pending meme content
- Approve/reject posts
- View content quality scores
- Track trending topics
- Keyboard shortcuts (← reject, → approve, ↓ skip)

### Local Development

Simply open `index.html` in a browser. Make sure your backend is running and CORS is configured to allow requests from your domain.
