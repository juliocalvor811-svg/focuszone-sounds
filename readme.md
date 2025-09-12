# 🎵 FocusZone Sounds Library
A curated collection of ambient sounds, binaural beats, and focus-enhancing audio for the FocusZone productivity app.

## 📁 Structure
focuszone-sounds/
├── binaural/ # Binaural beats for different brain states (5 files)
├── nature/ # Natural ambient sounds (5 files)
├── noise/ # Technical noises for focus (3 files)
└── urban/ # City and indoor ambiences (2 files)

text

## 🎧 Sound Library

### Binaural Beats (Requires Headphones)

| File | Frequency | Purpose | Best For |
|------|-----------|---------|----------|
| alpha-waves-10hz.mp3 | 10 Hz | Relaxed Focus | Reading, Learning |
| beta-waves-14hz.mp3  | 14 Hz | Alert Concentration | Daily Tasks |
| beta-waves-20hz.mp3  | 20 Hz | Intense Focus | Problem Solving |
| gamma-waves-40hz.mp3 | 40 Hz | Peak Performance | Complex Tasks |
| theta-waves-6hz.mp3  | 6 Hz | Creative Flow | Brainstorming |

### Nature Sounds

| File | Description | Best For |
|------|-------------|----------|
| rain-light.mp3      | Gentle rain | Reading, Writing |
| ocean-waves.mp3     | Beach waves | Relaxation |
| forest-ambience.mp3 | Birds & leaves | Calm focus |
| thunderstorm.mp3    | Rain with thunder | Deep work |
| birds-chirping.mp3  | Morning birds | Light tasks |

### Noise Generators

| File | Type | Best For |
|------|------|----------|
| white-noise.mp3 | Full spectrum  | Blocking distractions |
| pink-noise.mp3  | Softer spectrum | Long study sessions |
| brown-noise.mp3 | Deep spectrum  | Deep concentration |

### Urban Ambience

| File | Environment | Best For |
|------|-------------|----------|
| cafe-ambience.mp3 | Coffee shop | Creative work |
| library-quiet.mp3 | Quiet library | Silent focus |

## 🚀 Usage

### Direct URL Access
const SOUND_BASE = 'https://raw.githubusercontent.com/juliocalvor811-svg/focuszone-sounds/main';

// Example: Play rain sound
const rainSound = new Audio(${SOUND_BASE}/nature/rain-light.mp3);
rainSound.play();

text

### Integration Example
const FocusZoneSounds = {
baseUrl: 'https://raw.githubusercontent.com/juliocalvor811-svg/focuszone-sounds/main',
sounds: {
// Binaural
'alpha-10hz': '/binaural/alpha-waves-10hz.mp3',
'beta-14hz': '/binaural/beta-waves-14hz.mp3',
'beta-20hz': '/binaural/beta-waves-20hz.mp3',
'gamma-40hz': '/binaural/gamma-waves-40hz.mp3',
'theta-6hz': '/binaural/theta-waves-6hz.mp3',

text
// Nature
'rain':      '/nature/rain-light.mp3',
'ocean':     '/nature/ocean-waves.mp3',
'forest':    '/nature/forest-ambience.mp3',
'thunder':   '/nature/thunderstorm.mp3',
'birds':     '/nature/birds-chirping.mp3',

// Noise
'white-noise': '/noise/white-noise.mp3',
'pink-noise':  '/noise/pink-noise.mp3',
'brown-noise': '/noise/brown-noise.mp3',

// Urban
'cafe':    '/urban/cafe-ambience.mp3',
'library': '/urban/library-quiet.mp3'
},
play(soundId) {
const url = this.baseUrl + this.sounds[soundId];
return new Audio(url);
}
};

text

## 📊 Technical Details
- **Format:** MP3  
- **Bitrate:** 128–192 kbps  
- **Total Size:** ~45 MB  
- **Hosting:** GitHub Raw  
- **License:** CC0 / Public Domain  

## 🔗 Direct Links
All sounds can be accessed directly via:

`https://raw.githubusercontent.com/juliocalvor811-svg/focuszone-sounds/main/[category]/[filename].mp3`

## 📱 App Integration
These sounds are designed for the FocusZone productivity app, providing:

- 🎯 Enhanced focus and concentration
- 🧘 Stress reduction
- 💡 Creativity boost
- 📚 Better study sessions
- 💤 Relaxation support

## 📄 License
All sounds in this repository are either:

- Created and released under CC0 (Public Domain)  
- Sourced from royalty-free libraries  

Free for commercial and personal use.

## 🤝 Contributing
Want to add more sounds? Please ensure:

1. Files are in MP3 format (128–192 kbps)  
2. Loops are seamless (no clicks or pops)  
3. Duration is 1–5 minutes for loops  
4. File size is under 10 MB  
5. License allows free commercial use  

## 📧 Contact
Created for FocusZone App by [@juliocalvor811-svg](https://github.com/juliocalvor811-
