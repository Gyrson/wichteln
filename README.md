# Secret Santa Decoder

A simple web page that allows participants to decode their Secret Santa assignments using the encrypted link they received.

## How to Use

1. Open the `index.html` file in a web browser
2. Paste your encrypted Secret Santa link into the text area
3. Click the "Decode Assignment" button
4. Your Secret Santa assignment will be displayed on the page

## Features

- Simple and intuitive interface
- Works offline (no internet connection required)
- Secure decoding of assignments
- Mobile-friendly design

## Technical Details

The decoder uses base64 decoding to reveal the assignment information. The encrypted link contains:
- The name of the person receiving the link
- The name of the person they should give a present to

## Security

The decoder is designed to only show the assignment for the person who received the link. It cannot be used to decode other people's assignments.

## Hosting on GitHub Pages

To host this decoder on GitHub Pages:

1. Create a new repository on GitHub
2. Push these files to the repository
3. Go to repository Settings > Pages
4. Enable GitHub Pages and select the main branch as the source
5. Your decoder will be available at `https://[your-username].github.io/[repository-name]` 
