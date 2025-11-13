 Audio_and_Speech_Processing

## Deploy to Render
1. Sign up at https://render.com
2. Create New → Web Service → Connect GitHub repo
3. Environment: Node
4. Build Command: npm install
5. Start Command: node backend/server.js
6. Add GOOGLE_APPLICATION_CREDENTIALS env variable
7. Deploy → Access live URL

## Google Cloud Setup
1. Enable Speech-to-Text & Text-to-Speech APIs
2. Create Service Account → Download JSON
3. Set env variable: GOOGLE_APPLICATION_CREDENTIALS="path_to_json"
