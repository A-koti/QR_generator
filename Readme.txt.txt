QR Code Generator
This is a single-page web application that allows users to generate QR codes for multiple Google Drive shareable links and download them as a single PDF. It’s designed to help manage vehicle-related files by creating scannable QR codes that link to cloud storage.
Features

Add multiple Google Drive shareable links.
Generate QR codes for each link.
Download all QR codes in a single PDF file.
Responsive design using Tailwind CSS.
Client-side processing with qrcode.js and jsPDF.

Prerequisites

A modern web browser (e.g., Chrome, Firefox).
No server setup required (runs client-side).

Usage

Upload vehicle-related files to Google Drive.
Set sharing to “Anyone with the link” and copy the shareable links.
Open index.html in a browser or host it (e.g., via GitHub Pages).
Paste one or more Google Drive links into the input fields.
Click “Add Another Link” to include more links if needed.
Click “Generate QR Codes” to preview the QR codes.
Click “Download QR Codes as PDF” to save all QR codes in a PDF.
Scan the QR codes to access the Google Drive files.

Setup
To run locally:

Clone the repository:
git clone https://github.com/your-username/vehicle-files-qr-generator.git


Open index.html in a browser.


To host on GitHub Pages:

Push the repository to GitHub.
Go to the repository’s Settings > Pages.
Set the source to the main branch and / (root) folder.
Access the site at https://your-username.github.io/vehicle-files-qr-generator.

Dependencies
Loaded via CDN:

Tailwind CSS
qrcode.js
jsPDF

Notes

Security: Ensure Google Drive links are not shared publicly if files are sensitive, as “Anyone with the link” makes them accessible.
Limitations: Direct Google Drive uploads require a backend; this app uses manual link input.

License
MIT License
