# Smart-City-Traffic-simulator
### Smart City Traffic Control Simulator

A highly interactive, client-side 2D traffic simulation that models vehicle physics, smart intersection management, queueing behavior, and emergency vehicle priority routing. Built entirely using Vanilla JavaScript, HTML5 Canvas, and Tailwind CSS. 

### 🚀 Features

* **Object-Oriented Physics Engine:** Real-time rendering of varied vehicle classes (Cars, Buses, and Ambulances) managing independent acceleration, dynamic speed variations, and bounds checking.
* **Micro-Collision Avoidance System:** High-precision distance tracking that allows vehicles to naturally queue behind stop lines and stacked cars without overlapping.
* **Smart Adaptive Routing (Emergency Mode):** Dynamic queue scanning that instantly overrides traffic loops to grant an automatic green-light corridor whenever an Emergency Ambulance is detected.
* **Live Analytical Dashboard:** Real-time calculation of key metropolitan metrics: 

  * Average Vehicle Waiting Time
  * Throughput Counter (Total Passed Vehicles)
  * Current System-wide Queue Length
* **Interactive Control Deck:** Manual controls to dynamically adjust green-light cycles, invoke heavy rush-hour flows, or inject emergency units instantly.

### 🛠️ Architecture & Core Components

* **Frontend Interface:** Structured layout powered by Tailwind CSS utility classes using a dark cyber-grid ecosystem.
* **Simulation Layer:** Double-buffered HTML5 Canvas components executing continuous calculation nodes inside a 60fps requestAnimationFrame loop.
* **State Management:** Fully client-side state machine handling active element buffers, dynamic time deltas, and data accumulation arrays entirely within volatile browser memory.

### 📂 Project Structure

text

├── index.html        # Single self-contained application entrypoint containing markup, custom CSS injection points, and operational JS logic blocks.
└── README.md         # Documentation and execution guide.

Use code with caution.

### ⚙️ Installation & Execution

Since the architecture relies strictly on zero-dependency client-side execution, you do not need any package managers (npm/yarn) or servers to spin it up: 

1. Clone the repository locally or download the source index.html file from Claude: 

bash

git clone https://github.com/YOUR_USERNAME/Smart-City-Traffic-Simulator.git

Use code with caution.
2. Navigate to the directory containing the file.
3. Open index.html directly using any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari).
