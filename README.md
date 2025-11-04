# smart-greenhose-managment-
<h1 align="center">🌿 Smart Monitoring of Greenhouse</h1>

<p align="center">
  <strong>An intelligent greenhouse monitoring system that uses sensors and neural networks for real-time environmental control.</strong>
</p>

<h2>📖 Overview</h2>
<p>
  The <b>Smart Monitoring of Greenhouse</b> project automates and optimizes greenhouse conditions by collecting sensor data (such as temperature, humidity, and soil moisture) and making intelligent decisions using a neural network embedded within an Arduino. 
  It ensures optimal plant growth while reducing manual intervention.
</p>

<h2>✨ Features</h2>
<ul>
  <li>Real-time monitoring of greenhouse parameters</li>
  <li>Neural network-based smart decision making</li>
  <li>Automatic control of actuators (fan, pump, lights)</li>
  <li>Sensor-based data collection and analysis</li>
  <li>Low-cost and energy-efficient system</li>
</ul>

<h2>⚙️ Tech Stack</h2>
<ul>
  <li><b>Microcontroller:</b> Arduino</li>
  <li><b>Language:</b> C/C++ (.ino)</li>
  <li><b>AI Model:</b> Embedded Neural Network</li>
  <li><b>Tools:</b> Wokwi Simulator / Arduino IDE</li>
  <li><b>Libraries:</b> As listed in <code>libraries.txt</code></li>
</ul>

<h2>🧠 Workflow</h2>
<ol>
  <li>Collect data from sensors (temperature, humidity, etc.)</li>
  <li>Feed data into the embedded neural network model</li>
  <li>Predict optimal actions for actuators</li>
  <li>Automatically control environmental factors</li>
  <li>Provide feedback for continuous adjustment</li>
</ol>

<h2>🚀 Getting Started</h2>
<ol>
  <li>Install the <b>Arduino IDE</b> and required libraries from <code>libraries.txt</code>.</li>
  <li>Open <code>sketch.ino</code> in Arduino IDE.</li>
  <li>Upload the code to your Arduino board or run the <b>Wokwi simulation</b>.</li>
  <li>Observe smart monitoring and automatic control in action.</li>
</ol>

<h2>📂 Project Structure</h2>
<pre>
smart monitoring of green house/
├── sketch.ino                # Main Arduino code
├── NeuralNetwork.cpp          # Neural network logic
├── NeuralNetwork.h
├── model_data.cpp             # Trained model data
├── model_data.h
├── libraries.txt              # Required Arduino libraries
├── diagram.json               # Circuit diagram
├── wokwi-project.txt          # Wokwi simulation config
└── README.md                  # Project documentation
</pre>
