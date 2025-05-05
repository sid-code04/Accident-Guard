# 🚨 Accident Guard

**Accident Guard** is a real-time accident detection and alert system designed to minimize the rate of road accidents by providing instant notifications to emergency services and family members. This project combines computer vision, geolocation tracking, and messaging services to detect accidents and send automated alerts when they occur.

## 🔍 Project Overview

This system captures real-time data through video feed, analyzes the footage to detect possible accidents using deep learning techniques, and triggers alerts via SMS to:

- 🚓 Nearest Police Station
- 🚑 Ambulance Services
- 👨‍👩‍👧 Family Members

## 🛠️ Technologies Used

- **Language:** Python
- **Environment:** Jupyter Notebook
- **Libraries and Frameworks:**
  - `OpenCV` – for video capturing and image processing
  - `Keras` – for deep learning and image classification
  - `NumPy`, `Pandas` – for data manipulation and mathematical operations
  - `Matplotlib`, `Pyplot` – for visualization
  - `Skimage` – for image transformation (resize)
  - `Twilio` – for sending SMS alerts
  - `Geocoder`, `Geopy` – for retrieving geolocation data
  - `Requests`, `OS`, `Math` – for API handling and basic operations

## 📦 Dependencies

Install the required dependencies using pip:

```bash
pip install opencv-python keras numpy pandas matplotlib scikit-image geopy geocoder twilio requests
```

##🚗 How It Works
Video Monitoring: Continuously captures video frames using a camera.

Accident Detection: Frames are preprocessed and passed to a trained deep learning model to detect signs of an accident.

Location Tracking: On detection, the system fetches the current location coordinates and translates them to a human-readable address.

SMS Alerts: Sends SMS messages to pre-configured contacts using Twilio API with accident details and location link.


##📈 Future Enhancements
Integration with GPS modules for embedded systems

Emergency contact management through web/mobile app

Real-time dashboard for monitoring multiple vehicles

Audio alerts and voice-based confirmation system


🤝 Contribution
Contributions are welcome! If you'd like to improve the system or fix bugs, feel free to fork the repo and raise a pull request.
