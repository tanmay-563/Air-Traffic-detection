✈️ Aircraft Closest Pair Detection
This project visualizes aircraft positions on a canvas and uses the Closest Pair Algorithm to detect and highlight the two aircraft closest to each other.

📚 Project Overview
🎨 Frontend: HTML, CSS, JavaScript (Canvas API).
📏 Algorithm: Closest Pair Detection using a Brute-force approach.
📊 Visualization: Aircraft positions visualized with a dynamic canvas.

🎯 Features
✅ Generate random aircraft positions.
✅ Identify and highlight the closest pair of aircraft.
✅ Display distance between the closest pair.
✅ Interactive canvas for real-time simulation.

🛠️ Tech Stack
Frontend: HTML, CSS, JavaScript (Canvas API)
Algorithm: Closest Pair Detection (JavaScript)

🚀 Setup Instructions
1️⃣ Clone the Repository
bash
Copy
Edit
git clone https://github.com/your-username/aircraft-closest-pair.git
cd aircraft-closest-pair
/DAA Final
├── /static
│   ├── /images
│   │   └── airplane.png
│   ├── style.css
│   └── script.js
└── index.html
3️⃣ Launch in Browser
Open index.html in your browser.
Click on Generate Aircraft and Find Closest Pair to run the simulation.
📦 Folder Structure
bash
Copy
Edit
/DAA Final
├── /static
│   ├── /images
│   │   └── airplane.png
│   ├── style.css
│   └── script.js
└── index.html
📊 Algorithm Explanation
Closest Pair Detection (Brute-force)
Time Complexity: 
𝑂(𝑛2)
O(n^2)
Steps:
Iterate over all possible pairs of aircraft.
Calculate Euclidean distance between each pair.
Track the minimum distance and the corresponding pair.
Draw a line connecting the closest pair on the canvas.

📸 Screenshots
<img src="static/images/screenshot.png" width="500" alt="Simulation Preview">
🤝 Contributing
Fork the repository.
Create a new branch:
bash
Copy
Edit
git checkout -b feature/your-feature
Commit your changes:
bash
Copy
Edit
git commit -m "Add your feature"
Push and create a Pull Request:
bash
Copy
Edit
git push origin feature/your-feature
