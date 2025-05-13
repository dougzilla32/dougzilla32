# TranslateGPT

TranslateGPT is an iOS application that enables real-time, bidirectional language translation for natural conversations between speakers of different languages.

> 🔒 Private Repository

---


![Swift](https://img.shields.io/badge/Swift-5.0-orange.svg)
![Platform](https://img.shields.io/badge/platform-iOS-blue.svg)
![License](https://img.shields.io/badge/license-MIT-green.svg)

## Real-time Language Translation in a Conversation Interface

TranslateGPT is an iOS application that enables real-time, bidirectional language translation for natural conversations between speakers of different languages. Supporting 44+ languages powered by AI language models, TranslateGPT breaks down communication barriers with a sleek, intuitive interface.

## Features

### Core Functionality
- **Real-time Translation**: Instantly translate spoken conversations between 44+ languages
- **Speech-to-Text**: High accuracy transcription even in noisy environments
- **Text-to-Speech**: Natural-sounding voice synthesis for translated content
- **Conversation Memory**: Full history of conversations maintained for context
- **Language Detection**: Automatic detection of spoken languages

### Innovative UI
- **Adaptive Layouts**: Multiple viewing arrangements (Opposed, Vertical, Horizontal) for different usage scenarios
- **Dynamic Orientation Control**: Automatic device orientation adjustment based on selected layout
- **Audio Visualization**: Real-time visual feedback during speech capture
- **Seamless Settings**: Contextual settings that appear when needed and hide automatically

### Technical Highlights
- **Core Data Integration**: Persistent storage for all conversation data
- **Swift Concurrency**: Advanced async/await patterns with timeout handling
- **Memory Management**: Efficient handling of audio processing and large language models
- **Error Handling**: Robust error recovery mechanisms for network failures and API limits
- **Real-time Stream Processing**: Custom filtering for audio streams

## Architecture

TranslateGPT follows a clean architecture pattern with Model-View-Controller principles:

- **Models**: `ContentModel`, `LanguageModel`, `Message`, etc.
- **Controllers**: `DataController` for CoreData management
- **Views**: Customized SwiftUI views with optimized performance

The application uses a combination of SwiftUI for the interface and Core Data for persistence, with specialized components for audio processing and API integration.

## Technical Stack

- **Swift 5** - Modern language features
- **SwiftUI** - Declarative UI framework
- **Core Data** - Persistence layer
- **Combine** - Reactive programming patterns
- **AVFoundation** - Audio handling
- **SwiftWhisper** - Speech recognition integration
- **GPT API Integration** - Natural language processing

## Screen Layouts

TranslateGPT offers three distinct conversation layouts to suit different usage scenarios:

1. **Opposed**: Face-to-face conversation mode with languages on opposite sides
2. **Vertical**: Stacked view with languages above/below each other
3. **Horizontal**: Side-by-side view optimized for landscape orientation

Each layout automatically adjusts device orientation and interface elements for optimal usability.

## Installation

To run TranslateGPT locally:

1. Clone the repository
2. Open `TranslateGPT.xcodeproj` in Xcode
3. Configure your API keys in `Configuration.swift`
4. Build and run on simulator or device

## Future Enhancements

- Offline translation capabilities
- Multi-party conversation support
- Enhanced language-specific idiom handling
- Cross-platform expansion to macOS and iPadOS

## License

TranslateGPT is available under the MIT license. See the LICENSE file for more info.

---

*Developed by Doug Stein*
