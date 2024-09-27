UPI QR Code Generator
This Python script generates QR codes for various UPI-based payment apps (PhonePe, Paytm, Google Pay) using a provided UPI ID. It allows users to create payment links for each app and saves the corresponding QR codes as image files.

Features
Generates UPI payment links for PhonePe, Paytm, and Google Pay.
Creates QR codes for each payment link.
Saves the QR codes as PNG image files.
Displays the generated QR codes.
Requirements
Python 3.x
qrcode library (You can install it using pip)
Installation
Clone the repository:

bash
Copy code
git clone https://github.com/your-username/upi-qr-generator.git
cd upi-qr-generator
Install the required Python libraries:

bash
Copy code
pip install qrcode[pil]
Usage
Run the script:

bash
Copy code
python qr_generator.py
When prompted, enter your UPI ID:

java
Copy code
Enter your UPI ID = example@upi
The script will generate three QR codes for PhonePe, Paytm, and Google Pay. The QR codes will be saved as:

phonepe_qr.png
paytm_qr.png
google_pay_qr.png
The generated QR codes will also be displayed for each payment app.

Example
Here's an example of how the QR code URLs are generated:

perl
Copy code
upi://pay?pa=example@upi&pn=Recipient%20Name&mc=1234
You can modify the URLs to include the recipient's name, amount, and any custom message you want.# QR-Code-generator
