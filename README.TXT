Bulk Image Captioner for LoRA Training
-------------------------------------
- Run `app.exe` to start the server.
- Get a Gemini API key at: https://makersuite.google.com/
- if Gemini API key is region blocked its because its the server you conected to is in wrong destination, test with another gmail
- when u find a gmail that works you can create one Key,
  and to create more keys with same Gmail make several projects that needs a Gemini key with that gmail in
  https://studio.firebase.google.com/

- Explaination video to make several keys:  https://www.youtube.com/watch?v=IdVgDHeNiEM

- Enter your Gemini API key and select images.
- Optionally enter a trigger word (leave blank for no prefix, or enter e.g., 'Rose' to prepend).
- Click "Generate Captions" to process images and download the ZIP file.
- The app creates `uploads` and `captions` folders in the same directory.
- Free Gemini API Quota: 50 requests/day, resets at 2:00 AM CEST.
- Note: NSFW content may sometimes fail due to API filtering. Retry or use a new API key if needed.