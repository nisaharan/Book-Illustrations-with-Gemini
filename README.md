# Book-Illustrations-with-Gemini

In this guide, you are going to use multiple Gemini features (long context, multimodality, structured output, file API, chat mode...) in conjunction with the Nano Banana image generation model to illustrate a book.

You will also explore how to bring your illustrations to life with:

🎬 Veo — Animate a chapter illustration into a short video
🎵 Lyria — Generate instrumental background music for each chapter
🗣️ TTS — Have a narrator read the opening of a chapter aloud
Each concept will be explained along the way, but if you need a simpler introduction to Gemini Image generation model, check the getting started notebook, or the Image generation documentation.

Note: for the sake of the notebook's size (and your billing if you run it), the number of images has been limited to 3 characters and 3 chapters each time, but feel free to remove the limitation if you want more with your own experimentations.

Also note that this notebook used to use Imagen models instead of Nano Banana. If you are interested in the Imagen version, checked-out this old version.

Note: Enable billing to use Image Generation. This is a pay-as-you-go feature (cf. pricing). This does not apply if you use gemini-2.5-flash-image (Nano Banana) which has a free tier.

This notebook also includes optional sections for Video generation (Veo), Music generation (Lyria), and Text-to-Speech (TTS) which are all paid features. Each has its own opt-in checkbox that you need to enable before running.

0/ Setup
This section install the SDK, set it up using your API key, imports the relevant libs, downloads the sample videos and upload them to Gemini.

Just collapse (click on the little arrow on the left of the title) and run this section if you want to jump straight to the examples (just don't forget to run it otherwise nothing will work).
