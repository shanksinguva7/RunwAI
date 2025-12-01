✈️ RunwAI: Runway Detection Interface

RunwAI is a modern web application designed to demonstrate high-precision semantic segmentation for runway detection in aerial imagery. This interface allows users to visualize the capabilities of a ResNet34-UNet model trained to identify airport runways with high accuracy.

🔗 Live Demo: Click here to view the Hugging Face Space

🚀 About The Project

Detecting runways in satellite or aerial imagery is a critical task for autonomous navigation and mapping. RunwAI bridges the gap between complex AI models and end-users by providing a clean, responsive React-based interface.

This website serves as the frontend visualizer for the deep learning backend, allowing users to interact with the model predictions seamlessly.

🧠 The AI Behind the App

The core intelligence of this application is powered by a ResNet34-UNet model developed by Sumukh Chakkirala.

Model Architecture: ResNet34-UNet

Input Resolution: 1920×1080

Performance:

IoU (Intersection over Union): 92.43%

Dice Score: 95.35%

Training Data: Trained on 3,987 high-resolution aerial images.

Check out the complete model repository and training details here: SumukhChakkirala/ai-yo

🛠️ Tech Stack

Frontend: React

Build Tool: Vite

Styling: CSS / Tailwind (if applicable)

Deployment: Hugging Face Spaces

💻 Getting Started

To run this project locally on your machine, follow these steps.

Prerequisites

Node.js (v14 or higher)

npm (v6 or higher)

Installation

Clone the repository

git clone [https://github.com/shanksinguva7/RunwAI.git](https://github.com/shanksinguva7/RunwAI.git)
cd RunwAI


Install dependencies

npm install


Run the development server

npm run dev


Open your browser and navigate to the local URL provided (usually http://localhost:5173).

📸 Screenshots
<img width="1343" height="838" alt="image" src="https://github.com/user-attachments/assets/c68eaddb-1ab4-473f-a6f4-94dce098215b" />


📄 License

This project is open source. Feel free to fork and contribute!
