# 🎯 Pasapalabra Rosco - The Ultimate Web Game

**Test your knowledge with the legendary letter wheel game!** 🔥

[🎮 Play Now](#features) • [📖 Documentation](#installation) • [🚀 Features](#features)

## 🌟 What is this?

Do you remember those afternoons watching Pasapalabra and thinking "I could do better!"? Well, here's your chance! 

This is a complete web game of the famous **Pasapalabra Rosco**, where you'll have to prove your general knowledge letter by letter, with the pressure of time running against you. ⏰

## ✨ Features

### 🎨 **Spectacular Design**
- 🟣 Purple gradient background that will mesmerize you
- 🫧 Organic bubbles for each letter with incredible visual effects
- 🔵 Current letter highlighted in bright blue
- ✅ Green for correct answers
- Gray for non answered questions
- ❌ Red for the ones... we'd rather not talk about

### 🎮 **Addictive Gameplay**
- ⌨️ **Super fast controls**: `O` key for correct, `K` key for incorrect
- 🖱️ **Also works with mouse** for the classics
- 📊 **Real-time statistics** that will make you nervous
- 🔄 **Automatic progression** - no unnecessary pauses

### ⏱️ **Epic Time System**
- ⚙️ **Configurable timer** - from 1 to 60 minutes
- 🔔 **Clock sound** in the last 10 seconds that will make you sweat
- 🎺 **Epic fanfare** when time runs out
- 💓 **Blinking timer** for the final drama

### 🎵 **Immersive Audio**
- 🔊 **Web Audio API** for crystal-clear sounds
- ⏰ **Realistic tick-tock** that increases tension
- 🎉 **Musical fanfare** with professional chords
- 🔇 **No external dependencies** - everything generated dynamically

## 🚀 Installation

### Option 1: Download and Ready
```bash
# Clone the repository
git clone https://github.com/yourusername/pasapalabra-rosco.git

# Enter the folder
cd pasapalabra-rosco

# Open the HTML file in your favorite browser
open index.html
```

### Option 2: Local Server (Recommended)
```bash
# If you have Python 3
python -m http.server 8000

# If you have Node.js
npx serve .

# Then go to http://localhost:8000
```

## 🎯 How to Play

### 🏁 **Setup**
1. **Set the time** - Are you brave? Set 2 minutes. Prefer to play it safe? 10 minutes is fine.
2. **Press "Start"** - And let the fun (and stress) begin.

### 🎮 **During the Game**
- **Blue letter = Your turn** - This is your chance!
- **Know the answer?** → Press `O` or the green button ✅
- **Have no clue?** → Press `K` or the red button ❌
- **Need a break?** → Pause button (though time is still your enemy)

### 📊 **Scoring**
- **Central percentage** - Your pride in numbers
- **Correct counter** - To brag about later
- **Wrong counter** - We prefer not to talk about this

## 🕹️ Controls

| Action | Keyboard | Mouse |
|--------|----------|-------|
| **Correct Answer** | `O` | 🟢 Green Button |
| **Pass Answer** | None |  Gray Button |
| **Incorrect Answer** | `K` | 🔴 Red Button |
| **Start Game** | - | 🎮 Start Button |
| **Pause/Resume** | - | ⏸️ Pause Button |
| **Reset** | - | 🔄 Reset Button |

## 🛠️ Technologies Used

- **HTML5** - The solid foundation
- **Advanced CSS3** - Gradients, animations and visual magic
- **JavaScript ES6+** - The logic that makes everything work
- **Web Audio API** - For those sounds that give you goosebumps
- **Flexbox & Grid** - Because responsive design is life
- **Keyframe Animations** - For those effects that bring it to life

## 🎨 Customization

### 🎨 **Change Colors**
Don't like purple? Change the CSS variables!
```css
:root {
  --primary-color: #667eea;    /* Your favorite color here */
  --secondary-color: #764ba2;   /* And another one here */
}
```

### ⏰ **Modify Times**
Want more adrenaline? Edit the limits:
```javascript
// In the HTML, change min and max of the input
<input type="number" min="1" max="120" value="5">
```

### 🔤 **Add/Remove Letters**
Playing in another language?
```javascript
this.letters = 'ABCDEFGHIJKLMNÑOPQRSTUVWXYZ'.split('');
// Change to your favorite alphabet
```

## 🐛 Troubleshooting

### 🔇 **No audio**
- Click anywhere on the page first
- Browsers need user interaction for audio

### 🐌 **Running slow**
- Use a modern browser (Chrome, Firefox, Safari, Edge)
- Close other resource-consuming tabs

### 📱 **Doesn't look good on mobile**
- Rotate device to landscape
- Use zoom to adjust size

## 🤝 Contributing

Got brilliant ideas? We love contributions!

1. **Fork** the project
2. **Create** a branch for your feature (`git checkout -b feature/brilliantIdea`)
3. **Commit** your changes (`git commit -m 'Add brilliant idea'`)
4. **Push** to the branch (`git push origin feature/brilliantIdea`)
5. **Open** a Pull Request

### 💡 **Ideas to Contribute**
- 🎵 More sound effects
- 🏆 Scoring system and records
- 🌍 Multiplayer mode
- 📱 Better responsive design
- 🎨 More visual themes
- 🧠 Different question categories

## 📜 License

This project is under the MIT license. Use it, modify it, share it and have fun!

## 🏆 Records and Challenges

### 🥇 **Speedrun Challenge**
- Can you complete all 27 letters in less than 2 minutes?
- With 100% accuracy?

### 🎯 **Precision Challenge**
- Can you achieve 95% accuracy or more?
- Without using the pause button?

### 🧠 **Knowledge Challenge**
- Can you guess which letters are statistically the most difficult?

## 📞 Contact and Support

Problems? Suggestions? Just want to say hello?

- 🐛 **Issues**: [GitHub Issues](https://github.com/yourusername/pasapalabra-rosco/issues)
- 💬 **Discussions**: [GitHub Discussions](https://github.com/yourusername/pasapalabra-rosco/discussions)
- 📧 **Email**: yourusername@example.com


**Let the game begin! 🎮**

*Will you be able to conquer the rosco?*

⭐ **If you like the project, give it a star** ⭐

## 🤖 Development Note

This project has been developed entirely using **Claude** (Anthropic's AI Assistant) as part of research into AI-assisted software development capabilities. The code, design, functionality, and this documentation were generated through conversational prompts, demonstrating the potential of human-AI collaboration in developing complete and interactive web applications.

*The era of AI-assisted programming is already here* 🚀

https://claude.ai/public/artifacts/bcdb8114-6e28-4a2e-943c-029c2a5127b0
