# Mi Primer Español

A simple web application designed to help toddlers learn basic Spanish phrases commonly used in daycare settings. The app features a series of scenes with corresponding audio phrases, making it easy and fun for young children to learn essential Spanish expressions.

## AI-Generated Content

This project is fully generated using various AI tools:
- Source code: Generated by Anthropic's Claude
- Images: Created using OpenAI's DALL-E
- Voice recordings: Generated using ElevenLabs

## Purpose

This project was created to help young children who are just starting their journey in a Spanish-speaking daycare environment. It focuses on common situations and basic phrases that children might need in their daily interactions with teachers and peers.

## Features

- Simple, child-friendly interface
- Large, clear illustrations for various daycare situations (AI-generated)
- Easy-to-use navigation with large touch areas
- Audio playback of Spanish phrases (AI-generated voices)
- Support for both touch gestures (swipe) and button navigation
- Works on both mobile devices and desktop browsers

## Getting Started

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/mi-primer-espanol.git
   ```

2. Update the `config.json` file in the root directory with your scenes:
   ```json
   {
     "scenes": [
       {
         "imageUrl": "path/to/image1.jpg",
         "audioUrl": "path/to/audio1.mp3"
       },
       {
         "imageUrl": "path/to/image2.jpg",
         "audioUrl": "path/to/audio2.mp3"
       }
     ]
   }
   ```

3. Run the local HTTP server or deploy to your preferred hosting service. To run the local HTTP server, use the following command:
   ```bash
   python3 -m http.server 8000
   ```

4. Open `http://localhost:8000` in a web browser or by url of your hosting service.

## Usage

- Tap/click the left or right side of the screen to navigate between scenes
- Tap the green "¡Escucha!" button to play the audio phrase
- Swipe left or right on mobile devices to navigate between scenes

## Technical Details

- Pure HTML/CSS/JavaScript implementation
- No external dependencies
- Mobile-first responsive design
- Touch-friendly interface

## Browser Support

The application works in all modern browsers:
- Chrome (recommended)
- Firefox
- Safari
- Edge

## License

MIT License - feel free to use and modify for your own needs.

## Contributing

Contributions are welcome! Feel free to submit issues and pull requests.

1. Fork the repository
2. Create your feature branch
3. Commit your changes
4. Push to the branch
5. Open a Pull Request

## Acknowledgments

This project demonstrates the potential of AI tools working together to create educational content:
- [Claude](https://www.anthropic.com/claude) by Anthropic - Source code generation
- [DALL-E](https://openai.com/dall-e-3) by OpenAI - Image generation
- [ElevenLabs](https://elevenlabs.io/) - Voice synthesis