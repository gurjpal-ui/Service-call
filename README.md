# On-Road Service Call Web App

A web-based service call form generator for Fountain Tire that creates professional PDF documents for each service call.

## Features

✅ Fill out service call details (date, time, customer info, driver details)
✅ Add multiple units requiring service (trailers, tractors, forklifts)
✅ Automatically generate PDF with professional formatting
✅ Dynamic filename generation based on date and customer name
✅ Responsive design for mobile and desktop
✅ Set dates/times to current values by default

## Files

- **index.html** - Main web form
- **style.css** - Styling with Fountain Tire branding (yellow/blue)
- **script.js** - Form logic and PDF generation
- **logo.jpeg** - Add your company logo here

## How to Use

1. Open `index.html` in your web browser
2. Fill in the service call details at the top (date, time, dispatcher, tech)
3. Enter customer/location information
4. Add unit details (type, number, tire size, position, notes)
5. Click "Generate PDF" to download the formatted document
6. Use "+ Add Another Unit" to include multiple units
7. Click "Clear Form" to reset all fields

## Setup

Make sure to add your Fountain Tire logo as `logo.jpeg` in the same directory as index.html.

The app uses:
- jsPDF library for PDF generation (CDN)
- Vanilla JavaScript (no dependencies needed locally)
- CSS Grid for responsive layout

## PDF Output

Generated PDFs include:
- Company logo and header
- Date and time of call
- Dispatcher and technician names
- Complete customer information
- Driver details
- All units and service requirements in a formatted table

## Supported Unit Types

- Trailer
- Tractor
- Forklift
- Other
