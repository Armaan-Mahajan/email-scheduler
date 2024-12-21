# Email Scheduler

A simple Python application using Tkinter that allows you to schedule emails to be sent at a specific time.

## Features
- Input recipient email, subject, content, and time to send the email.
- Sends the email automatically at the specified time.
- Uses `smtplib` to send emails via your email provider's SMTP server.

## Setup

1. Clone the repository:
    ```bash
    git clone https://github.com/your-username/email-scheduler.git
    ```

2. Install the required dependencies:
    ```bash
    pip install tk
    ```

3. Edit the script to include your email provider’s details:
    - SMTP host
    - Port
    - Login credentials
    - Your email address

4. Run the script:
    ```bash
    python email_scheduler.py
    ```

## How to Use
- Enter the recipient's email address, subject, and content.
- Set the time in 24-hour format (e.g., `14:30:00`).
- Click "Schedule Email" to send the email at the specified time.
