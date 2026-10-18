# Fics-Aurally
Yes, the title is a reference to Nyota Uhura's pun in Star Trek XI // A fanfic reader, because who wouldn't want to listen to their yaoi fics on the road?
------------------------------------------------------------------------------------------------
# Fics,Aurally

**Fics,Aurally** is a multi-voice fanfiction TTS reader built using SwiftUI for iPadOS and Swift Playgrounds. It automatically distinguishes narration, dialogue, and internal thoughts, assigning distinct regional voices and voice properties to each.

## Features
- Reads rich-text clipboard data (`public.html`) directly from Safari (or any other browser, if you'd like), converting `<em>` and `<i>` tags into `*asterisks*` for  monologues.
- **Text Reading but With signs because I (for the love of me) can't differentiate what's talking, what's thoughts, and what's narration:**
  - **Narration:** Default US English voice.
  - **Dialogue (`"..."`):** Default UK English voice.
  - **Internal Thoughts (`*...*`):** Default Australian English voice with lower pitch and volume.
- Color-coded text and auto-scrolling!
- Fully editable, compilable, and executable directly on an iPad without Xcode or a Mac (ekhem.)

## Requirements
- iPad on iPadOS 16.0 or later vers
- [Swift Playgrounds](https://apps.apple.com/app/swift-playgrounds/id1498632822) installed on iPad.

## Setup Instructions
1. Clone/download this repo, Unzip it.
2. Open the project directly inside **Swift Playgrounds** on iPad.
3. Ensure no default `@main` conflicts exist if replacing files.
4. Tap **Play (▶️)** to run the app.
