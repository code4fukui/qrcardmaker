# qrcardmaker (QR名刺メーカー)

> 日本語のREADMEはこちらです: [README.ja.md](README.ja.md)

A simple, client-side web application for generating vCard QR codes. Fill in your contact details to create a QR code for your digital business card.

## Demo

**Live application:** [https://code4fukui.github.io/qrcardmaker/](https://code4fukui.github.io/qrcardmaker/)

## Features

*   Generates vCard 3.0 QR codes from user input.
*   Input fields for Name, Phonetic Name (Furigana), Organization, Email, URL, Address, and Phone Number.
*   Runs entirely in the browser; no data is sent to a server.
*   Simple, responsive interface built with vanilla HTML, CSS, and JavaScript.
*   Single-file application with no build process required.

## Usage

1.  Open the [demo page](https://code4fukui.github.io/qrcardmaker/).
2.  Enter your contact information into the provided fields.
3.  Click the **"QR生成"** (Generate QR) button.
4.  A QR code will appear below the button.
5.  Scan the QR code with your smartphone's camera to import the contact details.

## Technical Details

The application captures the input field data and formats it into a v