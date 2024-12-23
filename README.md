# Automated WhatsApp Message Sender

## Description
This Python script automates sending WhatsApp messages using the `pywhatkit` library. It's a handy tool for scheduling messages without manual intervention, making it ideal for reminders, greetings, or other time-sensitive notifications.

---

## Features
- Send personalized messages to any WhatsApp contact.
- Schedule messages for a specific time.
- Requires minimal setup and runs directly in the terminal.

---

## Tech Stack
- Python
- `pywhatkit` library

---

## Usage

### 1. Install Dependencies
Ensure you have Python installed. Then, install the required library using:
```bash
pip install pywhatkit
```

### 2. Edit the Script
Modify the following lines in the `msgfrnd.py` file to set your recipient’s phone number, message, and the time to send:
```python
pywhatkit.sendwhatmsg("+91XXXXXXXXXX", "Your Message Here", HH, MM)
```
Replace:
- `+91XXXXXXXXXX` with the recipient’s phone number.
- `"Your Message Here"` with your desired message.
- `HH, MM` with the hour and minute (24-hour format) for sending the message.

### 3. Run the Script
Execute the script using:
```bash
python msgfrnd.py
```

### 4. Keep the System Active
Ensure your system remains active until the message is sent, as the script relies on your active WhatsApp Web session.

---

## Example
The current script sends a message:
- **To**: `+91778*******`
- **Message**: `Hi`
- **At**: `14:29` (2:29 PM)

---

## Disclaimer
- This script is intended for educational and personal use only.
- Ensure you have the recipient's consent before sending automated messages.
