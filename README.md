# Furbish Translator

A simple web app that translates English text into **Furbish**, the playful language of the Furby toy line.

## Features

- **Dictionary-based translation**: Uses an English→Furbish word list from official sources.
- **Phrase templates**: Recognizes certain canonical phrases (e.g., *Are you hungry?* → *u-nye-ay-tay-doo?*).
- **Boosters**: Words like "very" or "really" map to the Furbish intensifier **dah**.
- **Fallback romanization**: Unknown words are converted into Furbish-like syllables so translation is never empty.
- **Confidence tagging**: Words are tagged as strong (dictionary), medium (templates/compounds), or low (fallback).

## Getting Started

1. Clone or download this repo to your local machine.
2. Open `index.html` in your browser.
3. Type English text in the left box and click **Translate →**.
4. See the Furbish translation in the right box.

## Example

**Input:**  
```
Are you hungry? I love my friend.
```

**Output:**  
```
u-nye-ay-tay-doo? kah may-may noo-lah.
```

## Project Structure

```
furbish-translator/
├── index.html   # Main app (HTML, CSS, JS in one file)
└── README.md    # Project documentation
```

## Future Improvements

- Expand the dictionary with more official Furbish words.
- Support reverse translation (Furbish → English).
- Add toggle for different Furby model vocabularies.
- Improve UI (Tailwind/React integration).

## Sources

Vocabulary and phrases drawn from official Furby manuals and Furbish word lists. See:  
- Furby Wiki: [Furbish Language](https://official-furby.fandom.com/wiki/Furbish_(language))

---

Have fun speaking Furbish with your friends!
