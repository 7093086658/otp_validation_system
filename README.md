DESCRIPTION

This Python script provides a simple OTP (One-Time Password) email verification system. 
It generates a random 4-digit OTP and sends it to a user-specified email using the Gmail SMTP server. 
The recipient must enter the correct OTP within three attempts to validate their identity.

FEATURES

Generates a 4-digit OTP randomly.

Sends OTP via email using Gmail's SMTP server.

Allows the user three attempts to enter the correct OTP.

Uses smtplib and email.mime modules to send emails.


USAGE

Update your email credentials securely.

Run the script:

python otp_email.py

Enter the recipient's email when prompted.

The recipient will receive an OTP.

Enter the received OTP in the terminal to validate.

Security Considerations

DO NOT hardcode credentials directly in the script. Use environment variables.

Use an App Password instead of your actual email p
