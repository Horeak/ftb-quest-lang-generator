# FTB Quest Language Generator

FTB Quest Language Generator is a Minecraft mod designed to generate language files in JSON format for the FTB Quest mod. It simplifies the process of creating and managing translations for custom quests, ensuring consistency and ease of integration into modpacks.

## Table of Contents

- [About](#about)
- [Features](#features)
- [Installation](#installation)
  - [Prerequisites](#prerequisites)
  - [Setup](#setup)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)

## About

This mod automates the generation of JSON language files for the FTB Quest mod. It processes quest data during runtime and produces properly formatted JSON files that are ready for integration into Minecraft modpacks.

## Features

- **Automated JSON File Generation**: Creates translation files in JSON format from quest data.
- **Seamless Integration**: Designed to work directly within Minecraft mod environments.
- **Multi-Language Support**: Easily generate translations for multiple languages.

## Installation

### Prerequisites

- **Minecraft Modding Environment**: Ensure you have a working Minecraft modding setup (e.g., IntelliJ IDEA or Eclipse with Minecraft Forge).
- **Java Development Kit (JDK)**: JDK 8 or higher.
- **Gradle**: Used for building the project.

### Setup

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/Horeak/ftb-quest-lang-generator.git
   cd ftb-quest-lang-generator
   ```

2. **Import the Project into Your IDE**:

   - Open the project in your preferred IDE.
   - Use the `build.gradle` file to configure the Gradle build.

3. **Build the Mod**:

   Compile and build the mod using Gradle:

   ```bash
   ./gradlew build
   ```

   The compiled mod will be located in the `build/libs` directory.

4. **Add to Your Minecraft Mods Folder**:

   Copy the `.jar` file from `build/libs` to your Minecraft `mods` folder.

## Usage

1. Install the mod alongside FTB Quests in your modpack.
2. Run the game to process your quest data.
3. The generated JSON language files will appear in the designated output directory, ready for integration into your modpack's localization.

## Contributing

As this repository is archived and read-only, contributions are no longer accepted. However, feel free to fork the repository for personal exploration and learning.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more details.
