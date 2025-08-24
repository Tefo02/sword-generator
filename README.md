# Sword Generator

A procedural 2D sword generator created with C++ using Cairo and SFML. The goal of this project is to allow users to generate unique, customizable swords with different attributes like length, curvature, width, and material.

## Features

- Procedural generation of sword shapes (curvature, length, width).
- Real-time preview with SFML.
- Customizable materials, gradients, and effects.
- Export generated swords as PNG or SVG.

## Installation

### Prerequisites

- CMake 3.10 or higher
- A C++ compiler (GCC, Clang, or MSVC)
- SFML
- Cairo

### Installation Steps

1. Clone this repository:

    ```bash
    git clone https://github.com/yourusername/sword-generator.git
    cd sword-generator
    ```

2. Install dependencies:

   - **Linux (Debian/Ubuntu):**
     ```bash
     sudo apt update
     sudo apt install build-essential cmake git libsfml-dev libcairo2-dev
     ```

   - **Windows (with vcpkg):**
     ```powershell
     git clone https://github.com/microsoft/vcpkg.git
     .\vcpkg\bootstrap-vcpkg.bat
     .\vcpkg\vcpkg install sfml cairo
     ```

3. Build the project:

   - **Linux:**
     ```bash
     cmake -S . -B build
     cmake --build build
     ```

   - **Windows (with vcpkg):**
     ```powershell
     cmake -B build -S . -DCMAKE_TOOLCHAIN_FILE="C:/path/to/vcpkg/scripts/buildsystems/vcpkg.cmake"
     cmake --build build
     ```

4. Run the executable:

   ```bash
   ./build/sword-generator

## Usage

- Once the tool is built, you can start the application and adjust various parameters (length, curvature, width, etc.) to generate your custom sword.

- You can then export the generated sword as a PNG or SVG file.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Contributing

Feel free to fork this repository and submit pull requests. Contributions are welcome to improve the generator, add more features, or fix bugs!

## Contact

For questions or suggestions, feel free to reach out through [GitHub Issues](https://github.com/Tefo02/sword-generator/issues).