# TokenGenerator
---

### Event Token Generator with QR Code

This Python project generates a unique QR code as a temporary event ID card for participants. Users can enter their name, roll number, department, and the event they wish to attend. The generated QR code contains all the entered details, serving as a digital ID that event managers can easily scan to validate participants.

#### Features
- **User Input**: Collects essential details like name, roll number, department, and event name.
- **QR Code Generation**: Encodes user details into a QR code using the `qrcode` library.
- **Temporary ID**: Acts as a temporary digital ID card valid for event entry.

#### Usage
1. Install the required libraries: `qrcode[pil]`
2. Run `generate_event_token()` to generate and save the QR code.
3. The generated QR code file can be scanned for participant verification at the event.

This project is an efficient solution for managing event participants without physical ID cards.
