# Bad-Libs

Automatically converts any book into a Mad-Libs style game of silliness.

This is a tutorial notebook to teach the basics of spaCy from scratch.

Requires:
 - Python 3
 - Jupyter notebook: https://jupyter.org/
 - spaCy: https://spacy.io

How it works:
 1. First it scans text for adjectives, nouns, verbs, people, and locations. 
 2. Then it creates placeholders that the "player" (that's you!) can provide their own answers for.
 3. It then fills-in-the blanks to replace the missing spots with a word of the appropriate part of speech.

Finally we read the finished bad-lib result while hilarity ensues.

#### Example:

```python
answers = [
    "Julia Roberts", # PERSON
    "shined", # Verb ending in "ed"
    "Rochester", # GPE
    "electrocuted", # Verb ending in "ed"
    "worm", # Singular noun
    "fiddled", # Verb ending in "ed"
    "butterflies", # Plural noun
    "trapped", # Verb ending in "ed"
    "pigeon", # Singular noun
    "singing", # Verb ending in "ing"
    "luckiest", # Adjective ending in "est"
    "horses", # Plural noun
    "shoehorns", # Plural noun
    "witnessed", # Verb ending in "ed"
    "blankets", # Plural noun
    "tested", # Verb ending in "ed"
    "leaping", # Verb ending in "ing"
    "pillow", # Singular noun
    "refridgerator", # Singular noun
]
```

_When Julia Roberts shined been down to Rochester and electrocuted his worm, he fiddled back to me at our butterflies, and trapped the pigeon to singing on me. He was the luckiest of horses, and at stated shoehorns witnessed off the blankets, and tested them in the leaping pillow that was kept ready, and put them on again, with a patient refridgerator that I was deeply grateful for._


