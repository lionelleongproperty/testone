# Real Estate Photo Enhancer (Local HTML UI)

A single-file local app (`index2.html`) that lets you:

- Upload up to **5 photos**.
- Select an **interior style profile**.
- Send each uploaded image to **OpenAI Image Edits** (`gpt-image-1`) with your real-estate enhancement prompt.
- Display and download the generated output images.

## Run locally

1. Open `index2.html` in a modern browser.
2. Upload up to 5 photos.
3. Select a style.
4. Enter your OpenAI API key.
5. Click **Generate with ChatGPT image editing**.

## Important note

Because this is a static local page, your browser directly calls the OpenAI API using your key.
For production use, route requests through your own backend so your API key is not exposed to end users.
