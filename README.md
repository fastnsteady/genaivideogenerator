# Gen AI video generator
Steps Followed in AI Video Generation Tool Project
1. Fetched Trending News Articles
• Used a news API (such as NewsData.io) to retrieve the latest
trending news articles.
• Extracted key fields: title, link, source, summary, content, publish
date, and image URL.
• Saved the fetched articles to a local JSON file for further
processing.
2. Selected a News Article
• Loaded the saved articles and displayed their headlines to the user.
• Allowed the user to select one article from the list for video
generation.
3. Generated a Short Video Script
• Used an AI language model to create a concise, engaging script
based on the selected article.
• Included a title, three main bullet points or key facts, an emotional
hook, a call-to-action, and scene descriptions for video/voiceover.
4. Parsed Script into Video Scenes
• Broke down the script into individual scenes, each with a
description and corresponding voiceover text.
5. Retrieved or Generated Visual Assets
• Searched for relevant images for each scene description using APIs
(such as SerpAPI, Pexels, or Unsplash).
• Ensured image URLs were accessible and used placeholders if
necessary.
6. Assembled Video Components
• Prepared selected images, voiceover text, background music
(optional), and text overlays (such as title, bullet points, and callto-action) for video generation.
TASK 1 - AI Video Generation Tool

7. Generated Video Using AI Video Tool
• Used a generative AI video tool or API (such as Creatomate) to
combine images, text overlays, and music into a short (30–60
second) video.
• Sent the prepared data (images, text, music) to the video generation
API and triggered the rendering process.
8. Monitored and Retrieved Final Video
• Polled the video generation API to check the rendering status.
• Retrieved the final video URL or file for download or sharing once
rendering was complete.
