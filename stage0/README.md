# Profile Card Project

A simple, responsive profile card web application that displays user information with social media links and real-time clock functionality.

## Project Overview

This project showcases a personal profile card with:
- User profile picture
- Name and bio
- Real-time clock display
- Social media links (Twitter, GitHub, Facebook, Instagram, TikTok)
- Hobbies and dislikes sections
- Responsive design that works on both mobile and desktop

## Features

- **Responsive Design**: Adapts to different screen sizes using CSS media queries
- **Real-time Clock**: Displays current timestamp using JavaScript
- **Social Media Integration**: Links to popular social platforms with SVG icons
- **Modern UI**: Clean, card-based design with gradient background
- **Accessibility**: Proper alt text for images and semantic HTML structure

## File Structure

```
├── index.html      # Main HTML structure
├── index.css       # Styling and layout
├── index.js        # JavaScript functionality
└── imag/
    └── profile_pic.jpg  # Profile picture
```

## Technologies Used

- HTML5
- CSS3 (with Flexbox and Media Queries)
- JavaScript (ES6)
- External SVG icons from [Simple Icons](https://simpleicons.org/)

## How It Works

1. The HTML file structures the profile card with semantic elements
2. CSS provides styling with a responsive layout that changes based on screen size
3. JavaScript updates the "Current Time" field with the current timestamp

## Setup and Usage

1. Clone or download this repository
2. Open `index.html` in your web browser
3. The profile card will display with the current time updating on page load

## Customization

To customize this profile card:

1. Replace `imag/profile_pic.jpg` with your own profile image
2. Update the name and bio in the HTML file
3. Modify social media links to point to your profiles
4. Adjust hobbies and dislikes sections as needed
5. Customize colors by modifying the CSS variables

## Responsive Behavior

- On screens smaller than 480px: Social links are centered
- On screens larger than 768px: Card layout changes to a horizontal arrangement

## License

This project is open source and available under the MIT License.