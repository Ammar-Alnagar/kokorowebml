title: Kokoro Text-to-Speech (WebGPU)
emoji: 🗣️⚡
colorFrom: yellow
colorTo: green
sdk: static
pinned: false
license: apache-2.0
short_description: High-quality speech synthesis powered by Kokoro TTS
header: mini
models:
  - onnx-community/Kokoro-82M-ONNX
custom_headers:
  cross-origin-embedder-policy: require-corp
  cross-origin-opener-policy: same-origin
  cross-origin-resource-policy: cross-origin
Kokoro Text-to-Speech (WebGPU)
A simple React + Vite application for running Kokoro, a frontier text-to-speech model for its size using Transformers.js.

Getting Started
Follow the steps below to set up and run the application.

1. Clone the Repository
Clone the examples repository from GitHub:

git clone https://github.com/hexgrad/kokoro.git
2. Navigate to the Project Directory
Change your working directory to the demo folder:

cd kokoro/kokoro.js/demo
3. Install Dependencies
Install the necessary dependencies using npm:

npm i
4. Run the Development Server
Start the development server:

npm run dev
The application should now be running locally. Open your browser and go to http://localhost:5173 to see it in action.
