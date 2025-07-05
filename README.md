# 🎉 Happy Birthday Website - Interactive Birthday Experience 🎂

<div align="center">
  <img src="img/favicon.png" alt="Birthday Icon" width="100" height="100">
  
  ### ✨ A Beautiful, Interactive Birthday Experience ✨
  
  *Say Happy Birthday in a nerdy, animated way!*
  
  ![HTML5](https://img.shields.io/badge/html5-%23E34F26.svg?style=for-the-badge&logo=html5&logoColor=white)
  ![CSS3](https://img.shields.io/badge/css3-%231572B6.svg?style=for-the-badge&logo=css3&logoColor=white)
  ![JavaScript](https://img.shields.io/badge/javascript-%23323330.svg?style=for-the-badge&logo=javascript&logoColor=%23F7DF1E)
  ![GSAP](https://img.shields.io/badge/GSAP-88CE02?style=for-the-badge&logo=greensock&logoColor=white)

  🔗 **[Live Demo](https://priyanshu84iya.github.io/Taniya-s-Birthday/)** | 📊 **[Repository](https://github.com/Priyanshu84iya/Taniya-s-Birthday)**
</div>

---

## 🌟 Features

### 🎭 **Interactive Animations**
- Smooth GSAP-powered animations that tell a story
- Sequential text revelations with beautiful transitions
- Flying balloons and floating elements
- Responsive design that works on all devices

### 🎵 **Audio Experience**
- Auto-playing birthday music (with user controls)
- Toggle music on/off with a beautiful button
- Immersive audio experience

### 🎨 **Customizable Content**
- Easy customization through `customize.json`
- Personalized messages, names, and images
- Change greetings, wishes, and special messages
- Add your own photos and personal touches

### 💫 **Beautiful UI/UX**
- Modern gradient backgrounds
- Elegant typography using Playfair Display font
- Smooth hover effects and interactions
- Mobile-responsive design
- Beautiful footer with social media links
- Interactive replay functionality

---

## 📸 Screenshots

<div align="center">
  
*Experience the magic of animated birthday wishes*

🎭 **Opening Animation** → 💬 **Interactive Chat** → 🎈 **Balloon Celebration** → 🎉 **Final Wishes**

*Visit the [Live Demo](https://priyanshu84iya.github.io/Taniya-s-Birthday/) to see it in action!*

</div>

---

## 🚀 Quick Start

### Prerequisites
- Node.js (for development server)
- A modern web browser

### Installation & Setup

1. **Clone or download this project**
   ```bash
   git clone https://github.com/Priyanshu84iya/Taniya-s-Birthday.git
   cd "Taniya's Birthday"
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start the development server**
   ```bash
   npm start
   ```

4. **Open your browser**
   - The website will automatically open at `http://localhost:7777`
   - If it doesn't open automatically, navigate to the URL manually

---

## 🎨 Customization Guide

### 📝 **Editing Content**
All customizable content is stored in `customize.json`. Simply edit this file to personalize the experience:

```json
{
  "greeting": "Hey",           // Opening greeting
  "name": "Pry Uchiha🎀",     // Birthday person's name
  "greetingText": "I really like your name btw!",
  "wishText": "May all your beautiful dreams blossom into reality! ✨🌟",
  "imagePath": "img/pry_uchiha.png",  // Profile image
  // ... and many more customizable options
}
```

### 🖼️ **Adding Images**
1. Place your images in the `img/` folder
2. Update the `imagePath` in `customize.json`
3. Supported formats: PNG, JPG, SVG

### 🎵 **Changing Music**
1. Replace `img/birthday_song.mp3` with your preferred audio file
2. Keep the same filename or update the HTML reference
3. Supported formats: MP3, WAV, OGG

### 👤 **Current Customization**
This project is currently customized for **Pry Uchiha** with:
- Custom profile image (`pry_uchiha.png`)
- Personalized messages and greetings
- Social media links in the footer
- Special birthday theme

To customize for someone else, simply update the `customize.json` file with new content!

---

## 📁 Project Structure

```
📦 Taniya's Birthday/
├── 🎵 img/                    # Images and audio assets
│   ├── ballon1.svg           # Balloon animations
│   ├── ballon2.svg
│   ├── ballon3.svg
│   ├── birthday_song.mp3     # Background music
│   ├── favicon.png           # Website icon
│   ├── hat.svg              # Birthday hat
│   └── pry_uchiha.png       # Profile picture
├── 📜 script/
│   └── main.js              # Animation logic & interactions
├── 🎨 style/
│   └── style.css            # Beautiful styling
├── 📄 index.html            # Main HTML structure
├── ⚙️ customize.json        # Customization data
├── 📦 package.json          # Project configuration
├── 🔒 package-lock.json     # Dependency lock file
└── 📖 README.md            # This file
```

---

## 🛠️ Technology Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Animations**: GSAP (GreenSock Animation Platform)
- **Development**: Browser-sync for live reloading
- **Fonts**: Google Fonts (Playfair Display)
- **Audio**: HTML5 Audio API

---

## 🎯 How It Works

1. **Page Load**: Fetches customization data from `customize.json`
2. **Content Injection**: Dynamically updates all text and images
3. **Animation Sequence**: GSAP triggers a beautiful animation timeline
4. **User Interaction**: Music controls and replay functionality
5. **Responsive Experience**: Adapts to different screen sizes

---

## 🎪 Animation Sequence

The website follows a carefully crafted animation timeline:

1. **🎭 Opening Greeting** - Animated text introduction
2. **💬 Chat Simulation** - Fake message box interaction
3. **✨ Special Message** - Personalized birthday wishes
4. **🖼️ Photo Reveal** - Profile picture with birthday hat
5. **🎈 Balloon Animation** - Flying balloons celebration
6. **🎉 Final Celebration** - Closing messages and replay option

---

## 🌐 Browser Support

- ✅ Chrome (recommended)
- ✅ Firefox
- ✅ Safari
- ✅ Edge
- ✅ Mobile browsers

---

## 📱 Mobile Responsive

The website is fully responsive and provides a great experience on:
- 📱 Smartphones
- 📱 Tablets
- 💻 Laptops
- 🖥️ Desktops

---

## 🚀 Deployment

This project is deployed using **GitHub Pages** and is automatically updated when changes are pushed to the main branch.

### Deploy Your Own Version:
1. Fork this repository
2. Go to repository Settings → Pages
3. Select "Deploy from a branch" 
4. Choose `main` branch and `/ (root)` folder
5. Your site will be available at `https://yourusername.github.io/Taniya-s-Birthday/`

### Local Development:
For local development with hot reload, use the npm start command which runs browser-sync on port 7777.

---

## 🤝 Contributing

Want to make this even more awesome? Here's how you can contribute:

1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

### Ideas for Contributions:
- 🎨 New animation effects
- 🎵 More audio options
- 🌟 Additional customization features
- 📱 Enhanced mobile experience
- 🎭 New themes and styles

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 👨‍💻 Created By

**Pry Uchiya** *(Priyanshu)*
- 📷 [Instagram](https://www.instagram.com/pry_uchiha/)
- 👻 [Snapchat](https://www.snapchat.com/add/pry.verse)
- 💻 [GitHub](https://github.com/Priyanshu84iya/)

---

## 🎉 Special Thanks

- **Everyone who inspires beautiful birthday celebrations** 🎂
- **GSAP (GreenSock)** - For amazing animation capabilities
- **Google Fonts** - For beautiful typography
- **Browser-sync** - For seamless development experience
- **The Open Source Community** - For continuous inspiration

---

<div align="center">
  
### 🎈 Made with ❤️ for special birthdays 🎈

*"Birthdays are nature's way of telling us to eat more cake and celebrate life!"*

---

**⭐ If you liked this project, please give it a star! ⭐**

</div>
