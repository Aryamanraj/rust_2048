# Tile Game

The Tile Game is a simple puzzle game where the objective is to combine numbered tiles to reach the highest possible score. The game is implemented in Rust using the Piston game engine and the OpenGL graphics library.

## Features

- Combine tiles of the same number to create new tiles with higher scores.
- Animated movement and creation of tiles for a visually appealing experience.
- Score tracking to keep track of the player's progress.
- Customizable settings for tile sizes, colors, and animation durations.
- User-friendly interface with keyboard controls for moving the tiles.

## Installation

To run the Tile Game, you need to have Rust and Cargo installed on your system. Follow these steps to get started:

1. Clone the repository:
    ```shell
   git clone https://github.com/Aryamanraj/rust_2048.git
    ```
2. Change into the project directory:
    ```shell
    cd tile-game
    ```
3. Build and run the game:
    ```shell
    cargo build && cargo run --release
    ```
The `--release` flag enables optimizations for a *smoother gameplay experience*.

## How to Play

- Use the arrow keys (up, down, left, right) to move the tiles in the corresponding direction.
- When two tiles with the same number collide, they combine into a new tile with the sum of their scores.
- The game ends when there are no more valid moves available (i.e., no empty spaces and no adjacent tiles with the same number).

## Customization

The Tile Game allows you to customize various aspects of the game to enhance your playing experience. You can modify the following settings:

- `board_size`: Adjust the size of the game board. Higher values create larger boards with more tiles. Default: 4.
- `target_score`: Set the target score to win the game. You can increase or decrease the challenge by adjusting this value. Default: 2048.
- `tile_colors`: Customize the colors of the tiles in the game. You can specify different colors for different tile values. Default: [List of default colors].
- `text_light_color` and `text_dark_color`: Define the colors for the text displayed on the tiles. Default: [Default light and dark colors].
- `tile_size`: Control the size of the tiles on the game board. Default: 100.
- `tile_padding`: Adjust the spacing between tiles. Default: 10.
- `board_padding`: Set the padding around the game board. Default: 20.
- `tile_new_time` and `tile_combine_time`: Adjust the animation duration for tile appearance and merging, respectively. Default: 0.15.
- `board_offset_y`: Offset the vertical position of the game board. Default: 100.

To customize these settings, open the `settings.rs` file in the source code and modify the values accordingly. Experiment with different settings to create your unique Tile Game experience!

Note: Make sure to rebuild and run the game after making any changes to the settings to see the customization in effect.

## License

The Tile Game is licensed under the [MIT License](LICENSE). Feel free to modify and distribute the game as per the terms of the license.

## Acknowledgements

The Tile Game is built using the following open-source libraries and frameworks:

- [Piston](https://www.piston.rs): A modular game engine for Rust.
- [Opengl_graphics](https://github.com/PistonDevelopers/opengl_graphics): An OpenGL back-end for Piston.
- [Number_renderer](https://github.com/Hoverbear/number_renderer): A library for rendering numbers in Rust.
- [Rand](https://github.com/rust-random/rand): A random number generator library for Rust.

We would like to express our gratitude to the developers of these libraries for their contributions to the open-source community.

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or bug reports, please feel free to open an issue or submit a pull request on the [GitHub repository](https://github.com/Aryamanraj/rust_2048).

When contributing to the Tile Game, please ensure that your code follows the existing coding style and conventions. Provide clear and concise explanations of the changes you've made and test your modifications thoroughly.

Thank you for your interest in contributing to the Tile Game!
