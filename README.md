# JSON Prompt Generator

A static web application for generating structured JSON prompts for LLM text-to-image models like DALL-E, Stable Diffusion, Midjourney, etc.

## Features

- User-friendly form to input prompt and select predefined parameters (style, lighting, mood, etc.)
- Support for custom keys and values
- Generates clean JSON output
- Copy to clipboard and download as .json file
- Local counter for generated JSONs
- Responsive design with Bootstrap
- Educational tooltips for each parameter
- Safari-compatible clipboard functionality

## How to Use

1. Open the application in your browser.
2. Enter a prompt in the "Prompt" field (required).
3. Optionally, enter a negative prompt.
4. Expand the accordions to select values for predefined keys or add custom keys.
5. Click "Generate JSON" to create the JSON.
6. View the output in the textarea.
7. Use "Copy to Clipboard" or "Download JSON" to save the result.
8. Use "Start Over" to reset the form.
9. The counter at the bottom shows how many JSONs have been generated in this browser.

## Deployment

The application is hosted on GitHub Pages at: https://sms1962.github.io/generatorJSON/

## Technologies Used

- HTML5, CSS3, Vanilla JavaScript
- Bootstrap 5 for UI components
- DOMPurify for input sanitization
- LocalStorage for counter

## Security

- Content Security Policy (CSP) implemented
- Input sanitization to prevent XSS
- Client-side only, no data sent to servers

## Development

To run locally:
1. Clone the repository
2. Open `index.html` in a browser

No build process required.

## License

This project is open-source. Feel free to use and modify.
