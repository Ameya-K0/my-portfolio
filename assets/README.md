# Assets Folder

This folder is for storing your portfolio assets such as:

## 📁 Recommended Structure

```
assets/
├── images/
│   ├── profile.jpg          # Your profile photo
│   ├── projects/            # Project screenshots
│   │   ├── project1.jpg
│   │   ├── project2.jpg
│   │   └── project3.jpg
│   └── logos/               # Company/university logos
│       └── university.png
├── documents/
│   ├── resume.pdf           # Your resume
│   └── transcripts/         # Academic transcripts
└── videos/
    └── project-demos/       # Project demonstration videos
        └── demo1.mp4
```

## 🖼️ Image Guidelines

- **Profile Photo**: 400x400px minimum, square format
- **Project Images**: 800x600px minimum, 16:9 or 4:3 aspect ratio
- **File Formats**: Use JPEG for photos, PNG for graphics with transparency
- **File Size**: Optimize images to keep file sizes under 2MB for web performance

## 📄 Document Guidelines

- **Resume**: Keep PDF under 2MB
- **File Naming**: Use descriptive names with hyphens (e.g., `resume-2024.pdf`)

## 🎥 Video Guidelines

- **Format**: MP4 is recommended for web compatibility
- **Resolution**: 1080p maximum for web viewing
- **Duration**: Keep demo videos under 2 minutes
- **File Size**: Compress videos to keep under 50MB

## 🔗 Usage in HTML

To use assets in your HTML:

```html
<!-- Profile Image -->
<img src="assets/images/profile.jpg" alt="Profile Photo">

<!-- Project Image -->
<img src="assets/images/projects/smart-home.jpg" alt="Smart Home Project">

<!-- Resume Link -->
<a href="assets/documents/resume.pdf" target="_blank">Download Resume</a>

<!-- Video Demo -->
<video controls>
    <source src="assets/videos/project-demos/demo1.mp4" type="video/mp4">
</video>
```

## 🚀 Deployment Note

All files in this folder will be included when you deploy to GitHub Pages. Make sure to optimize file sizes for web performance.
