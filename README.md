# Cyber Security Toolkit

A comprehensive web application that combines website compliance checking and image watermarking capabilities. Built with React, TypeScript, and Tailwind CSS.

## Features

### Website Compliance Checker
- Check websites for compliance with various security standards and regulations
- Detailed analysis of:
  - GDPR Compliance
  - Cookie Consent
  - SSL/TLS Security
  - Data Protection
  - Access Control
  - Server Security
- Visual status indicators (pass, warning, fail)
- Detailed recommendations for improvement
- Real-time compliance checking

### Image Watermarking System
- Embed invisible watermarks in images
- Extract watermarks from watermarked images
- Preview original and watermarked images
- Support for various image formats
- Secure watermarking algorithm
- Easy-to-use interface

## Technologies Used

- React 18
- TypeScript
- Tailwind CSS
- Vite
- Jimp (JavaScript Image Processing)
- Crypto-js
- React Tabs
- Lucide Icons

## Getting Started

1. Clone the repository:
```bash
git clone <repository-url>
cd cyber-security-toolkit
```

2. Install dependencies:
```bash
npm install
```

3. Start the development server:
```bash
npm run dev
```

4. Build for production:
```bash
npm run build
```

## Usage

### Website Compliance Checker
1. Enter the website URL you want to check
2. Click "Check Compliance"
3. Review the detailed compliance report
4. Follow recommendations for improvement

### Image Watermarking
1. Choose between "Embed Watermark" or "Extract Watermark"
2. Upload an image
3. For embedding:
   - Enter watermark text
   - Click "Embed Watermark"
   - Download the watermarked image
4. For extraction:
   - Upload a watermarked image
   - Click "Extract Watermark"
   - View the extracted watermark text

