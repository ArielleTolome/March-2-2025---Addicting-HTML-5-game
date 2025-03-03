# Quick Catch - Reflex Game

A fun HTML5 reflex game where players tap or click on objects before they disappear, while avoiding red objects.

## Audio Support

Due to browser autoplay policies, users need to interact with the game before audio can play. When you first load the game, you'll see a "Click to Start Game with Audio" button. Clicking this button enables the background music and sound effects.

### Audio Troubleshooting

If you experience issues with audio playback after deployment:

1. Check the browser console for any error messages related to audio
2. Try using the included `audio-test.html` page to test audio playback directly
3. Ensure your browser allows autoplay of media with sound
4. Try different browsers to see if the issue is browser-specific

## Deployment to Vercel

This project is configured for easy deployment to Vercel. Follow these steps to deploy:

### Option 1: Deploy with Vercel CLI

1. Install Vercel CLI if you haven't already:
   ```
   npm install -g vercel
   ```

2. Navigate to the project directory and run:
   ```
   vercel
   ```

3. Follow the prompts to complete the deployment.

### Option 2: Deploy via GitHub

1. Push this project to a GitHub repository.

2. Go to [Vercel Dashboard](https://vercel.com/dashboard).

3. Click "New Project" and import your GitHub repository.

4. Vercel will automatically detect the configuration and deploy your game.

### Option 3: Deploy via Drag and Drop

1. Go to [Vercel Dashboard](https://vercel.com/dashboard).

2. Drag and drop the entire project folder onto the dashboard.

## Project Structure

- `index.html` - The main game file containing HTML, CSS, and JavaScript
- `Echoes In Time.mp3` - Background music for the game
- `vercel.json` - Configuration file for Vercel deployment

## Game Controls

- Click or tap on objects to catch them
- Avoid red objects
- Use the pause button to pause the game
- Use the sound button to toggle sound on/off