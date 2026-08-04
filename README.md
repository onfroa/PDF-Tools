# PDF Tools

A fast, private, and responsive collection of PDF utilities that runs directly in your web browser.

**Live website:** [pdf-tools-auy.pages.dev](https://pdf-tools-auy.pages.dev/)

## About

PDF Tools lets users convert, organize, and edit PDF files without installing additional software. File processing happens locally in the browser, so selected images and PDFs are not uploaded to a server.

## Tools and Functions

### 1. JPG to PDF

Convert JPG, PNG, and other supported image files into PDF documents.

- Upload multiple images at once.
- Drag and drop images to rearrange their page order.
- Choose portrait or landscape orientation.
- Select a page size, including Fit to Image, A4, Letter, Legal, and A3.
- Choose no margin, small margin, or big margin.
- Select the output image quality.
- Merge all images into one PDF or create a separate PDF for every image.
- Preview each image and remove unwanted files before conversion.

### 2. PDF to JPG

Turn PDF pages into JPG images.

- Upload a PDF and preview its pages.
- Convert every PDF page into a JPG image.
- Download individual page images.
- Download all converted pages together as a ZIP file.

### 3. Edit PDF

Make page-level changes to a PDF before saving a new copy.

- Preview all pages in the document.
- Rearrange pages using drag and drop.
- Rotate pages.
- Delete unwanted pages.
- Insert blank pages.
- Add pages from another PDF.
- Save the edited document as a new PDF file.

> This tool edits PDF pages and their order. It does not directly rewrite existing text inside a page.

### 4. Merge PDF

Combine multiple PDF documents into one file.

- Upload several PDF files.
- Drag and drop files to choose the correct order.
- Preview the uploaded documents.
- Remove unwanted files before merging.
- Download the combined PDF.

### 5. Split PDF

Extract selected pages from a PDF.

- Preview every page in the uploaded PDF.
- Select the pages you want to extract.
- Create one PDF containing all selected pages.
- Save selected pages as separate PDF files in a ZIP archive.

## Main Features

- Private, browser-based file processing
- No account or database required
- No file uploads to a server
- Drag-and-drop file and page ordering
- Responsive desktop and mobile layouts
- Fixed mobile action button for easier conversion
- Dark interface with hover animations
- Automatic downloads after processing
- Single-page application with no installation required

## Privacy

Uploaded files stay in the current browser session and are processed on the user's device. The website does not currently include a database, user accounts, cloud storage, or conversion history. Closing or refreshing the page clears the selected files.

## Technologies Used

- HTML5
- CSS3
- JavaScript
- jsPDF
- PDF-lib
- PDF.js
- JSZip
- Cloudflare Pages

The required JavaScript libraries are included in the HTML file, allowing the main tools to run without loading external library files.

For the best experience, use a current version of Chrome, Edge, Firefox, Brave, or Safari. Very large files may take longer to process because conversion depends on the device's available memory and processing power.

## Project Status

The website currently includes five working tools:

1. JPG to PDF
2. PDF to JPG
3. Edit PDF
4. Merge PDF
5. Split PDF

