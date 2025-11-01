
- Search YouTube videos using keywords
- Fetch titles, thumbnails, and descriptions
- Uses `fetch()` to call YouTube API
- API key is **secured** using `.env` (not leaked publicly)
- Deployed and running as a **Serverless Function** on Vercel


How to run locally:
 
 1.Clone the repository
   git clone https://github.com/Anushka666666/youtube-api-fetcher.git
   
   cd youtube-api-fetcher

 2️. Install dependencies
    npm install

 3️. Create .env file
     YT_API_KEY=YOUR_GOOGLE_API_KEY
     
4. Run the server
    vercel --prod


   LIVE DEMO:https://youtube-api-9kwft09s0-anushkancs-9138s-projects.vercel.app/api/search?query=cricket
