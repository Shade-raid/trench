# Trench Commander

> A WWI trench management survival game inspired by *Blackadder Goes Forth*

![Version](https://img.shields.io/badge/version-1.0.0-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)
![Open Source](https://img.shields.io/badge/open%20source-yes-brightgreen.svg)

## 🎮 About

**Trench Commander** is a dark comedy survival game set in the trenches of World War I. You play as a junior officer managing Section 12-B, trying to keep your men alive while navigating absurd orders from High Command, dealing with the horrors of trench warfare, and maintaining the delicate balance between duty and self-preservation.

Heavily inspired by the sardonic humor of *Blackadder Goes Forth*, this game captures the absurdist "lions led by donkeys" narrative of the Great War.

## 🎯 Gameplay

Manage three critical resources:
- **Morale** - Keep your men's spirits up despite the circumstances
- **Supplies** - Ammunition, rations, and equipment
- **Readiness** - Your section's combat effectiveness

Face 15+ unique events including:
- Suicidal attack orders from generals in châteaux
- Probing attacks and artillery bombardments
- Weather conditions and disease outbreaks
- Supply shortages and inspections
- Moral dilemmas and bureaucratic absurdities

Make tough choices where every decision has consequences. Survive as long as possible without:
- Mutiny (morale reaches 0)
- Starvation (supplies reach 0)
- Being overrun (readiness reaches 0)
- Decimation (50+ casualties)

## 🚀 Features

- **Single HTML file** - No installation, no dependencies, no build process
- **Works offline** - Download once, play anywhere
- **Mobile responsive** - Works on desktop, tablet, and phone
- **Period-authentic aesthetic** - Vintage WWI design with weathered paper textures
- **Dark humor** - Blackadder-style sardonic wit
- **Replayability** - Random events mean each playthrough is different

## 💻 Technical Details

- **Pure vanilla JavaScript** - No frameworks, no libraries
- **HTML5 + CSS3** - Modern web standards
- **~500 lines of code** - Simple, readable, hackable
- **No server required** - Runs entirely in the browser
- **No analytics or tracking** - Your privacy is respected

## 📦 Installation & Usage

### Option 1: Download and Play
1. Download `trench-commander.html`
2. Open it in any modern web browser
3. Start playing!

### Option 2: Host It
Upload the HTML file to any web server or GitHub Pages. It's just one file!

### Option 3: Customize It
The entire game is in a single HTML file. Open it in any text editor and modify:
- Add new events (search for the `events` array)
- Adjust difficulty (modify starting stats)
- Change the aesthetic (edit CSS in `<style>` tags)
- Add new game mechanics (JavaScript in `<script>` tags)

## 🛠️ Customization Guide

### Adding New Events

Find the `events` array in the JavaScript section and add:

```javascript
{
    title: "YOUR EVENT TITLE",
    text: "Event description with period-appropriate dark humor.",
    choices: [
        { text: "First option", morale: -10, supplies: 5, readiness: 0 },
        { text: "Second option", morale: 5, supplies: -10, readiness: 10 },
        { text: "Third option", morale: 0, supplies: 0, readiness: -5 }
    ]
}
```

### Modifying Difficulty

Change initial values in the `gameState` object:

```javascript
let gameState = {
    day: 1,
    morale: 70,    // Change starting morale
    supplies: 60,  // Change starting supplies
    readiness: 50, // Change starting readiness
    // ...
};
```

### Styling Changes

All CSS is in the `<style>` section. Modify colors, fonts, or layout to taste.

## 🎨 Design Philosophy

This game was designed to be:
- **Accessible** - Anyone can play it without downloads or accounts
- **Hackable** - Source code is readable and modifiable
- **Respectful** - Uses historical distance (100+ years) for dark comedy
- **Educational** - Subtly illustrates the absurdity and tragedy of WWI
- **Free** - No ads, no tracking, no monetization

## 📜 License

This project is released under the **MIT License**.

```
MIT License

Copyright (c) 2025 Trench Commander Contributors

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
```

**TL;DR:** You can do whatever you want with this code. Modify it, sell it, use it for school projects, fork it, break it, improve it. Just don't sue us.

## 🤝 Contributing

This is an open-source project and contributions are welcome!

### Ways to Contribute:
- **Add new events** - More variety makes the game more replayable
- **Improve the writing** - Better jokes, more authentic period language
- **Balance adjustments** - Tweak difficulty and stat changes
- **Bug fixes** - Find something broken? Fix it!
- **Translations** - Want to translate to another language?
- **Accessibility improvements** - Better screen reader support, keyboard navigation
- **Mobile optimization** - Better touch controls

### How to Contribute:
1. Fork this repository
2. Make your changes
3. Test thoroughly
4. Submit a pull request with a clear description

Or just:
1. Download the HTML file
2. Make your changes
3. Share your version!

Since it's MIT licensed, you don't need permission. Just make cool stuff!

## 🎓 Educational Use

This game is perfect for:
- **History classes** - Illustrates WWI trench warfare conditions
- **Game design courses** - Simple example of choice-based gameplay
- **Web development learning** - Clean example of vanilla JS/HTML/CSS
- **Ethics discussions** - Explores moral dilemmas in wartime

Teachers and educators: Feel free to use, modify, or distribute this game in your classes.

## 🙏 Acknowledgments

- **Blackadder Goes Forth** - For the inspiration and tone
- **WWI historians** - For documenting the realities of trench warfare
- **Open source community** - For making the web a better place

## 📬 Contact & Support

- Found a bug? Open an issue!
- Have an idea? Share it!
- Made something cool with this code? We'd love to see it!

## 🌟 Why Open Source?

This game is open source because:

1. **Education** - Others can learn from the code
2. **Preservation** - The game won't disappear if I do
3. **Improvement** - Community contributions make it better
4. **Freedom** - You own your copy completely
5. **Transparency** - No hidden trackers or data collection
6. **Sharing** - Good ideas should be shared, not locked up

If you enjoy this game, the best way to support it is to:
- Share it with others
- Contribute improvements
- Make your own version
- Teach others to code with it

## 📊 Stats

- **File size:** ~50KB uncompressed
- **Lines of code:** ~500
- **Dependencies:** 0
- **Build process:** None
- **Runtime requirements:** Modern web browser
- **Players needed:** 1
- **Time to play:** 5-20 minutes per session

---

**Made with dark humor and vanilla JavaScript**

*"Good luck out there, Commander. Try not to die stupidly."*
