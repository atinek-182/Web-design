# Premier Model Management

An editorial fashion agency landing page built with semantic HTML5 and modern CSS3. The layout draws inspiration from high-fashion print magazines, incorporating fluid typography, video backgrounds, and horizontal marquee scrollers.

## Live deployment

View the live website on Vercel:
[https://web-design-one-red.vercel.app](https://web-design-one-red.vercel.app)

## Full page preview

Full-page desktop capture (1920px width) of the deployed site:

![Premier Model Management Full Page Preview](./assets/preview.jpg)

## Features

- Video hero banner: Autoplay looping video with overlay titles and navigation cues.
- Continuous circular scroller: Infinite horizontal image reel showcasing model portraits.
- Alphabetical index: Interactive A to Z filter bar for talent discovery.
- Editorial feature grids: Multi-column story cards highlighting magazine spreads and fashion profiles.
- Updates timeline: Categorized agency updates organized by category and date.
- Movie shot showcase: Media-rich photography and film portfolio layout.
- Horizontal marquee: Typography banner highlighting annual agency archives.
- Editorial blog: Multi-column publication articles with drop-cap accents.
- Responsive layout: Fluid scaling using viewport width units and structured CSS grid and flexbox properties.

## Technologies used

- HTML5: Semantic page structuring.
- CSS3: Viewport-based fluid typography, custom keyframe animations, flexbox, and grid layouts.
- Remix Icon: Vector icons for search, navigation, and social links.

## Local development

To run this project locally on your machine:

1. Clone the repository:
   ```bash
   git clone https://github.com/atinek-182/Web-design.git
   ```

2. Navigate into the project directory:
   ```bash
   cd Web-design
   ```

3. Open `index.html` directly in your browser, or start a local development server:
   ```bash
   # Using Python 3
   python -m http.server 3000

   # Or using Node.js npx serve
   npx serve .
   ```

4. Visit `http://localhost:3000` in your web browser.

## Project structure

```text
Project CSS/
|-- assets/
|   \-- preview.jpg          # Full-page desktop preview (1920px width)
|-- arrow-right.png          # UI navigation icons
|-- arrow-right-black.png
|-- circle-text.png          # Rotating typography assets
|-- circle-text2.png
|-- img1.jpg - img31.jpg     # Editorial campaign photography
|-- index.html               # Main website markup
|-- style.css                # Core stylesheets and animations
|-- vid.webm                 # Hero background video
\-- README.md                # Project documentation
```
