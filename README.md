# Afternoon Nap - Interactive Film Experience

## Overview
"Afternoon Nap" is an interactive web-based film experience that tells the story of Mahlet, a meticulous roommate, and her interactions with her laid-back roommate Naz. The project combines traditional filmmaking with interactive storytelling, allowing viewers to make decisions that influence the narrative's direction.

## Features

### 1. Interactive Storytelling
- Branching narrative system with multiple story paths
- Decision points where viewers can choose different actions
- Seamless video transitions based on user choices
- Linear back-navigation system through the story

### 2. Modern User Interface
- Responsive design that works across desktop and mobile devices
- Elegant animations and transitions
- Custom video player controls
- Interactive rating system with visual feedback
- Behind-the-scenes content section

### 3. Cast & Team Sections
- Detailed cast member profiles
- Team showcase with floating card animations
- Behind-the-scenes video integration
- Responsive grid layout for team members

### 4. User Experience Features
- Dynamic rating system with facial expression feedback
- Smooth navigation with hamburger menu for mobile
- Animated background elements
- Social proof section with ratings and reviews

## Technical Stack

- **Frontend:**
  - HTML5
  - CSS3 (with advanced animations and responsive design)
  - JavaScript (vanilla JS for interactivity)
  - YouTube Player API for video handling

- **External Dependencies:**
  - Font Awesome 6.0.0-beta3 for icons
  - YouTube iFrame API for video playback

## Project Structure

```
.
├── index.html          # Main HTML file
├── style.css          # Main stylesheet
├── script.js          # JavaScript functionality
├── Images/            # Image assets directory
│   ├── Afra.jpg
│   ├── Iqra.jpg
│   ├── Mahlet.jpg
│   └── Naz.jpg
└── Videos/            # Video content directory
```

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/Mahlet333/Afternoon_Nap_Movie.git
   ```

2. No build process is required as this is a static website.

3. Serve the files using a local web server:
   - You can use Python's built-in server:
     ```bash
     python -m http.server 8000
     ```
   - Or any other static file server

4. Open your browser and navigate to:
   ```
   http://localhost:8000
   ```

## Interactive Video Navigation

The interactive video system follows these rules:
1. Initial video (1.MOV) plays and shows decision options
2. Based on user choice:
   - "Text Her" path leads to 2.MOV
   - "Clean It Yourself" path leads to 3.MOV
3. Back navigation is available from 2.MOV/3.MOV onwards
4. Linear navigation ensures proper story flow

## Responsive Design Breakpoints

- Desktop: > 1024px
- Tablet: 701px - 1024px
- Mobile: ≤ 700px
- Small Mobile: ≤ 500px

## Team

- **Iqra** - Web Designer and Developer
  - Senior | Class of 2026
  - Double Major: Interactive Media & Psychology
  - Contact: ib2419@nyu.edu

- **Mahlet** - Web Developer & Actor
  - Senior | Class of 2026
  - Major: Computer Science & Mathematics
  - Contact: ma7030@nyu.edu

- **Naz** - Editor, Camera & Actor
  - Senior | Class of 2025
  - Major: Computer Engineering
  - Contact: ic2268@nyu.edu

- **Afra** - Cast
  - Senior | Class of 2027
  - Major: Interactive Media & Design
  - Contact: aab8407@nyu.edu

## Browser Compatibility

Tested and optimized for:
- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Android Chrome)

## Known Issues

- Back button navigation from 4.MOV may show decision overlay incorrectly
- Some mobile devices may require additional optimization for video playback

## Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## License

This project is part of an academic work at NYU. All rights reserved.

## Acknowledgments

Special thanks to:
- The entire cast and crew
- NYU faculty and staff
- Everyone who participated in user testing and provided feedback 
