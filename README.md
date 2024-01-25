# Smart Home Security System

## Project Overview
This project is inspired by the notification system of a Samsung smart fridge. It involves a Raspberry Pi-based smart camera installed at the front door, equipped with SIM support for network independence and a UPS for power backup. The system integrates with a home alarm to enhance security by detecting motion and sending push notifications when no one is at home. I will add pictures from my actual setup.

## Key Features
- **Motion Detection**: Activates when the home alarm system is turned on.
- **Push Notifications**: Sends alerts for motion detected in front of the door.
- **Network Independence**: Uses a SIM module for secure communication.
- **Power Redundancy**: A UPS provides up to 30 minutes of backup power.

## Hardware Components
- **Raspberry Pi 4 Model B**: Main controller for the camera system.
- **Mini-Camera Module**: For capturing live footage.
- **SIM Card Module**: Allows network connectivity without Wi-Fi (e.g., Twilio SIM).
- **UPS (Uninterruptible Power Supply)**: Provides power backup.

## Software Components
- **Home Assistant**: Open-source home automation platform for system integration.
- **Frigate NVR**: Real-time object detection system used for motion detection.
- **Google Coral**: For enhanced object recognition capabilities.

## Setup and Installation

### Raspberry Pi Setup
1. **Assemble the Hardware**: Connect the mini-camera, SIM card module, and UPS to the Raspberry Pi.
2. **Install the Operating System**: Use Raspberry Pi OS or a suitable alternative.

### Software Configuration
1. **Home Assistant**: Install and configure Home Assistant for home automation integration.
2. **Frigate NVR**: Set up Frigate for real-time video monitoring and object detection.
3. **Motion Detection**: Configure the system to detect motion and trigger alerts.

### Network and Connectivity
1. **SIM Card Activation**: Activate the SIM card with a provider like Twilio.
2. **Network Configuration**: Set up the Raspberry Pi to use the SIM card for network access.

### Power Backup
1. **UPS Configuration**: Ensure the UPS is properly connected and configured for automatic power backup.

## Usage
- Turn on the home alarm system to activate the camera.
- Receive push notifications on your smartphone for any detected motion.

## Security and Privacy
- Ensure all communications are encrypted.
- Regularly update all software components to the latest versions.

## Troubleshooting
- **Camera Not Working**: Check the camera connections and ensure proper power supply.
- **No Notifications**: Verify network connectivity and Home Assistant configurations.

## Contributing
Feedback and contributions to this project are welcome. Please open an issue or pull request on the project's GitHub repository.

## License
[MIT License](https://opensource.org/licenses/MIT) - Feel free to use and modify this project as per the MIT License guidelines.
