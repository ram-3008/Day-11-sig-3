Day 11: Simple Temperature Classifier

This project uses an ESP32 to classify temperature readings as Low, Medium, or High with a small dense neural network. The ESP32 prints each test reading, its predicted class, and the model’s confidence scores to the Serial Monitor.

Components

ESP32 DevKit board Classification Labels
Low: below 20°C
Medium: 20°C to 30°C
High: above 30°C
Wokwi Simulation Create an ESP32 project in Wokwi and add these files from the repository:

sketch.ino
diagram.json
How to use

Start the Wokwi simulation.
Open the Serial Monitor at 115200 baud.
View the sample temperature readings, predicted classes, and confidence scores.
Edit the testTemps array in sketch.ino to try different readings.

Run the simulation[https://wokwi.com/projects/476963536994525185]
