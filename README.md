# Omar Mukthar - Talent Acquisition Leader Portfolio

## 📁 File Structure

```
omar/
├── Omar Mukthar – Talent Acquisition Leader.html    # Main portfolio page
├── assets/
│   └── documents/
│       └── Omar_Mukthar_CV.pdf                      # CV file for download
├── Omar Mukthar – Talent Acquisition Leader_files/  # Original assets
└── README.md                                        # This file
```

## 📄 Adding CV Files

### Option 1: Replace the existing CV file (Recommended)
1. **Replace** `assets/documents/Omar_Mukthar_CV.pdf` with your actual CV
2. **Supported formats**: PDF, DOC, DOCX, TXT
3. **File naming**: Keep the same filename or update the HTML link

### Option 2: Add multiple CV formats
You can add multiple CV files in different formats:

```
assets/documents/
├── Omar_Mukthar_CV.pdf          # Primary CV (PDF)
├── Omar_Mukthar_CV.docx         # Word format
├── Omar_Mukthar_CV.txt          # Text format
└── Omar_Mukthar_Resume.pdf      # Alternative resume
```

Then update the HTML to include multiple download options:

```html
<div class="dropdown">
    <button class="dropdown-toggle">Download CV</button>
    <div class="dropdown-menu">
        <a href="assets/documents/Omar_Mukthar_CV.pdf" download>PDF Version</a>
        <a href="assets/documents/Omar_Mukthar_CV.docx" download>Word Version</a>
        <a href="assets/documents/Omar_Mukthar_CV.txt" download>Text Version</a>
    </div>
</div>
```

### Option 3: Use external hosting
If you prefer to host your CV elsewhere:

1. **Google Drive**: Upload CV and get shareable link
2. **Dropbox**: Upload CV and get direct download link
3. **LinkedIn**: Use LinkedIn profile as CV source

Update the HTML link:
```html
<a href="https://drive.google.com/uc?export=download&id=YOUR_FILE_ID" download>
    Download CV
</a>
```

## 🚀 Features

- **Responsive Design**: Works on all devices
- **Modern UI**: Clean, professional design
- **jQuery Functionality**: Interactive elements and animations
- **Smooth Scrolling**: Enhanced navigation experience
- **Download Functionality**: Direct CV download with progress indication

## 📱 Browser Compatibility

- Chrome (Recommended)
- Firefox
- Safari
- Edge
- Mobile browsers

## 🔧 Customization

### Changing CV File
1. Replace `assets/documents/Omar_Mukthar_CV.pdf`
2. Update the filename in HTML if needed
3. Test the download functionality

### Adding More Documents
1. Place files in `assets/documents/`
2. Update HTML links accordingly
3. Consider adding a document gallery section

## 📞 Support

For any issues or questions about the portfolio:
- Email: omarmukthar2324@gmail.com
- LinkedIn: https://www.linkedin.com/in/omarmuktharb/

---

**Note**: The current CV file is a sample. Please replace it with your actual CV content. 
