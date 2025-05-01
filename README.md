
📸 Mosaic Selfie App — Android Java (Legacy Project)
"Thousands of memories form a single face." — Mosaic App

🧠 Overview
This Android app allows you to create a mosaic portrait made entirely of your photos. The process uses camera input or an existing selfie and overlays it with a grid of tiny images — selected based on color dominance — to reconstruct your face from your memories.

💡 Features
📷 Camera access with transparent cut-out overlay for framing selfies

🖼 Option to choose a selfie from your gallery instead of taking one

🗂 Load a source image folder for mosaic tile selection

🎨 Analyze the selfie into a grid of dominant pixel colors (default: 10x10)

🧩 Reconstruct the selfie using your images by:

Matching each grid color to the closest image in your folder

Overlaying them with soft blending for artistic effect

⏳ Includes a loading screen (process takes 2–3 minutes)

🖼 Final result is saved to device as a single, mosaic-style image

🔐 Permissions
This app requires:

📁 Storage access: to load source images and save results

📸 Camera access: to take a new selfie

(Optionally: gallery access to pick a selfie manually)

🛠️ How It Works
App launches, asks for permissions

Opens camera with a border overlay for face alignment

User takes or selects a selfie

User selects a source image folder

The app:

Extracts dominant color in each 10×10 square of the selfie

Reduces your source images to similar size

Matches each tile to the nearest color

Builds a final image tile by tile

Result: a mosaic portrait of your selfie, composed of the memories you selected

📷 Example Result

Each pixel tells a story.
