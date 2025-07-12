# JSON Resume Tech Theme

[![npm version](https://img.shields.io/npm/v/jsonresume-theme-tech.svg)](https://www.npmjs.com/package/jsonresume-theme-tech)
[![npm downloads](https://img.shields.io/npm/dm/jsonresume-theme-tech.svg)](https://www.npmjs.com/package/jsonresume-theme-tech)

> A professional, ATS-optimized JSON Resume theme for software engineers, tech professionals, and startup founders.

This modern, clean theme is specifically designed for technical professionals who want to showcase their skills and experience in a format that is both human-readable and ATS (Applicant Tracking System) friendly. Perfect for software engineers, senior developers, tech leads, CTOs, and startup founders.

## 🚀 Features

- **ATS-Optimized Layout**: Ensures your resume passes through Applicant Tracking Systems
- **Clean Typography**: Improves readability and visual appeal
- **Responsive Design**: Looks great on all devices and when printed
- **Technical Focus**: Highlights programming skills, projects, and technical achievements
- **Customizable Sections**: Easily adapt to showcase your unique experience

## 📋 Installation & Usage

This theme is compatible with [resumed](https://github.com/rbardini/resumed), a powerful command-line tool for managing, previewing, and publishing your JSON Resume.

### Sample Commands

```bash
# Install resumed globally
npm install -g resumed

# Initialize a new resume in the current directory
resumed init

# Preview your resume with the tech theme
resumed preview --theme tech

# Build your resume to HTML with the tech theme
resumed build --theme tech

# Export your resume to PDF with the tech theme
resumed export --theme tech
```

Make sure to install this theme in your project:

```bash
npm install --save jsonresume-theme-tech
```

## ⚙️ Customization Options

This theme offers special formatting options to better showcase your technical skills and experience. For the "experience" and "skills" sections, you can optionally replace the standard "highlights" list with a more detailed "details" list format:

```
"details": [
  { "text": "Javascript", "comment": "expert" },
  { "text": "Coffeescript", "comment": "expert" },
  { "text": "Ruby", "comment": "competent" },
  { "text": "Java", "comment": "novice" }
]
```

See the included resume.json for more examples and detailed formatting options.

## 🔗 Related Projects

- [JSON Resume](https://jsonresume.org/) - The open source initiative to create a JSON-based standard for resumes
- [resumed](https://github.com/rbardini/resumed) - Command line tool for easily updating and publishing resumes

## 📄 License

MIT

