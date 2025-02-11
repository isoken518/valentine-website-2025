# 💝 Valentine's Day Website 2025 💝

[![Stars](https://img.shields.io/github/stars/End2EndAI/valentine-website-2025?style=social)](https://github.com/End2EndAI/valentine-website-2025/stargazers)
[![Fork](https://img.shields.io/github/forks/End2EndAI/valentine-website-2025?style=social)](https://github.com/End2EndAI/valentine-website-2025/fork)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Tweet](https://img.shields.io/twitter/url?style=social&url=https%3A%2F%2Fgithub.com%2FEnd2EndAI%2Fvalentine-website-2025)](https://twitter.com/intent/tweet?text=%F0%9F%92%9D%20Create%20your%20own%20Valentine%27s%20website%20for%20free%21%20No%20coding%20required%21%0A%F0%9F%8E%81%20Fully%20customizable%2C%20easy%20to%20deploy%20with%20your%20own%20website%20name%0A%E2%9C%A8%20Try%20it%20now%3A%20https%3A%2F%2Fgithub.com%2FEnd2EndAI%2Fvalentine-website-2025%0A%23ValentinesDay2025%20%23WebDev%20%23GitHub%20%23Love)


valentineName: "Collins"                    // Your Valentine's name
pageTitle: "Will You Be My Valentine? 💝" // Browser tab title

// Floating Background Elements
floatingEmojis: {
    hearts: ['❤️', '💖', '💝', '💗', '💓'],  // Heart emojis in background
    bears: ['🧸', '🐻']                       // Bear emojis in background
}

// Questions and Buttons
questions: {
    first: {
        text: "Do you like me?",                   // First question
        yesBtn: "Yes",                             // Yes button text
        noBtn: "No",                               // No button text
        secretAnswer: "I don't like you, I love you! ❤️"  // Hidden message
    },
    second: {
        text: "How much do you love me?",          // Second question
        startText: "This much!",                   // Text before percentage
        nextBtn: "Next ❤️"                         // Next button text
    },
    third: {
        text: "Will you be my Valentine...?",      // Final question
        yesBtn: "Yes!",                            // Yes button text
        noBtn: "No"                                // No button text
    }
}

// Love Meter Messages
loveMessages: {
    extreme: "WOOOOW You love me that much?? 🥰🚀💝",  // Shows above 5000%
    high: "To infinity and beyond! 🚀💝",              // Shows above 1000%
    normal: "And beyond! 🥰"                           // Shows above 100%
}

// Final Celebration
celebration: {
    title: "Yay! I'm the luckiest person...",     // Celebration title
    message: "Now come get your gift...",          // Celebration message
    emojis: "🎁💖🤗💝💋❤️💕"                        // Celebration emojis
}

// Website Colors
colors: {
    backgroundStart: "#ffafbd",      // Background gradient start
    backgroundEnd: "#ffc3a0",        // Background gradient end
    buttonBackground: "#ff6b6b",     // Button color
    buttonHover: "#ff8787",          // Button hover color
    textColor: "#ff4757"            // Text color
}

// Animation Settings
animations: {
    floatDuration: "15s",           // How long hearts float (10-20s)
    floatDistance: "50px",          // Sideways movement (30-70px)
    bounceSpeed: "0.5s",            // Bounce animation speed (0.3-0.7s)
    heartExplosionSize: 1.5         // Final heart explosion size (1.2-2.0)
}

// Music Settings
music: {
    enabled: true, // Music feature is enabled
    autoplay: true, // Try to autoplay (note: some browsers may block this)
    musicUrl: "YOUR_CLOUDINARY_URL_HERE", // Paste your music URL here
    startText: "🎵 Play Music", // Button text to start music
    stopText: "🔇 Stop Music", // Button text to stop music
    volume: 0.5 // Volume level (0.0 to 1.0)

### 3. Adding Your Own Background Music 🎵

Want to make it extra special with your own romantic song? Follow these steps to add background music:

1. **Get a Cloudinary Account (Free):**
   - Go to [Cloudinary.com](https://cloudinary.com) and sign up for a free account

2. **Upload Your Music:**
   - Log in to your Cloudinary dashboard
   - Click on the "Upload" button in the top right
   - Select "Upload" from the dropdown menu
   - Choose your MP3 file (keep it under 10MB for better loading)
   - Wait for the upload to complete

3. **Get Your Music URL:**
   - After upload, find your music file in the Media Library
   - Click the "..." (more options) button on your music file
   - Click "Copy URL"
   - Select "Copy Original URL with options"
   - The URL should look like: `https://res.cloudinary.com/your-cloud-name/video/upload/v1234567890/your-file-name.mp3`

4. **Add to Your Website:**
   - Open `config.js`
   - Find the `music` section
   - Replace the `musicUrl` value with your Cloudinary URL

```javascript
music: {
    enabled: true,
    autoplay: true,
    musicUrl: "YOUR_CLOUDINARY_URL_HERE", // Paste your URL here
    startText: "🎵 Play Music",
    stopText: "🔇 Stop Music",
    volume: 0.5
}
```


