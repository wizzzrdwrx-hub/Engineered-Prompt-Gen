# Engineered-Prompt-Gen
Engineered-Prompt-Gen
A comprehensive, single-file HTML web application designed to architect highly structured, advanced prompts for AI image generation models. It specializes in generating complex internal visualizations, technical diagrams, architectural cutaways, and structural studies.

Features
Multi-Domain Targeting: Tailor prompts specifically for Biological, Mechanical, Architectural, or Cybernetic subjects, complete with custom negative prompts to prevent domain-specific artifacts (e.g., preventing "messy wires" in cybernetics or "gore" in biologicals).

Precise Camera & Styling Controls: Dropdown selections for camera framing, structural focus, lighting engines (e.g., volumetric vs. radiographic), and aesthetic environments.

Gemini API Integration (AI Assist):

✨ Enhance Subject: Automatically expands a basic subject (like "complex engine") into a highly detailed, evocative phrase tailored for image generation.

✨ Suggest Tags: Analyzes the chosen lighting and visual mode to generate 3-5 expert-level stylistic keywords (e.g., rendering engines, lens types).

✨ Auto-Palette: Invents a highly specific, custom color palette tailored to the exact concept being generated.

Live Updating: The final prompt box updates in real-time as you tweak parameters.

Zero Dependencies: Runs entirely in the browser using vanilla HTML, CSS, and JavaScript.

Setup & Installation
Clone or Download: Clone this repository or download the index.html file directly.

API Key Setup (Required for AI Features): * Obtain a Gemini API key from Google AI Studio.

Open index.html in a text editor.

Locate the const apiKey = ""; variable near the top of the <script> tag.

Paste your key inside the quotes: const apiKey = "YOUR_API_KEY_HERE";

⚠️ SECURITY WARNING: Do not commit your actual API key to a public GitHub repository. If you plan to host this publicly, you must implement a backend proxy to securely handle API requests.

Run: Simply double-click index.html to open it in any modern web browser.

Usage
Select Core Subject: Choose a domain (Biological, Mechanical, etc.) and enter a specific subject. Use the "✨ Enhance" button to let the LLM flesh out the description.

Configure Style & Camera: Select your desired cutaway style, camera angle, and structural focus.

Dial in the Polish: Choose your environment and lighting. Use the "✨ Auto-Palette" to generate a unique color scheme, and "✨ Suggest Tags" to append professional rendering keywords.

Copy & Paste: Click "Copy Full Prompt" and paste it into your image generation model of choice (Midjourney, DALL-E 3, Stable Diffusion, etc.).

License
This project is open-source and available under the MIT License.