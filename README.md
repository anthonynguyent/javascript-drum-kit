# javascript-drum-kit

This project is a simple drum kit implemented using JavaScript. It allows users to play drum sounds by pressing specific keys on their keyboard. Each key corresponds to a specific drum sound, and pressing the key triggers the corresponding sound and visual effect.

## Getting Started

To use the drum kit, follow these steps:

1. Clone the repository or download the source code files.
2. Open either the `index-START.html` or `index-FINISHED.html` file in a web browser.
3. Press the keys A, S, D, F, G, H, J, K, or L on your keyboard to play different drum sounds.
4. Enjoy creating your own beats!

## Prerequisites

To run the drum kit, you need a modern web browser with JavaScript support.

## Usage

The drum kit provides a visual representation of each drum sound and the corresponding key to press. When a key is pressed, the associated drum sound is played, and the key element is highlighted to provide feedback.

## Customization

You can customize the drum kit by modifying the `index-START.html` and `style.css` files.

### Adding or Changing Sounds

To add or change drum sounds, follow these steps:

1. Prepare the audio file for the new sound in the WAV format.
2. Add an `<audio>` element in the HTML code, inside the `<body>` section, for the desired key. Use the `data-key` attribute to specify the key code associated with the sound.
3. Set the `src` attribute of the `<audio>` element to the file path of the sound.
4. Make sure to update the JavaScript code to handle the new key and audio element.

### Modifying Styles

To modify the visual style of the drum kit, you can edit the `style.css` file. The CSS code controls the appearance of the keys and their behavior when interacted with. Feel free to customize the colors, dimensions, borders, and other properties to match your preferences.

### Changing Background Image

If you want to change the background image, replace the existing `background.jpg` file in the project directory with your desired image file. Update the CSS code in the `style.css` file to refer to the new background image file.

## Demo

You can view a live demo of the project [here](https://anthonynguyent.github.io/javascript-drum-kit/).

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgements

The drum kit project is inspired by Wes Bos's JavaScript30 course, which teaches JavaScript by building small projects. Special thanks to Wes Bos for the inspiration and guidance.

## Contact

If you have any questions, suggestions, or feedback, please feel free to reach out to [your email address] or create an issue in the GitHub repository.

Happy drumming!
