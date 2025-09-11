const README_CONTENT = `
# FocusZone Sounds Library

## 📁 Structure
- **/binaural**: Binaural beats for different brain states
- **/nature**: Natural ambient sounds
- **/noise**: Technical noises for focus
- **/urban**: City and indoor ambiences

## 🎵 Usage
\`\`\`javascript
const SOUND_BASE_URL = 'https://raw.githubusercontent.com/juliocalvor811-svg/focuszone-sounds/main';

// Example usage
const rainSound = \`\${SOUND_BASE_URL}/nature/rain-light.mp3\`;
\`\`\`

## 📊 Sound Details
| File | Duration | Size | Best For |
|------|----------|------|----------|
| alpha-waves-10hz.mp3 | 10:00 | 4.5MB | Relaxed learning |
| white-noise.mp3 | 5:00 | 2.3MB | Deep focus |
| rain-light.mp3 | 3:00 | 2.8MB | Reading |
| cafe-ambience.mp3 | 2:00 | 3.2MB | Creative work |

## 📝 License
All sounds are CC0 or freely available for commercial use.
`;

// 2. ARCHIVO DE CONFIGURACIÓN
const SOUNDS_CONFIG = `
// sounds.json
{
  "baseUrl": "https://raw.githubusercontent.com/juliocalvor811-svg/focuszone-sounds/main",
  "categories": {
    "binaural": {
      "name": "Binaural Beats",
      "icon": "🧠",
      "sounds": [
        {
          "id": "alpha-10hz",
          "file": "alpha-waves-10hz.mp3",
          "name": "Alpha 10Hz",
          "description": "Relaxed focus and learning",
          "duration": "10:00",
          "size": "4.5MB"
        }
        // ... más sonidos
      ]
    }
    // ... más categorías
  }
}
`;
