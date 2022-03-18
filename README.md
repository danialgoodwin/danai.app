# DAN AI

A few ideas for my AI. Not necessarily machine learning.


- AI is a programming language that understands itself
    - 'What is var x'
    - 'Given x, what is y'
- AI doesn't need to start by knowing English
    - It's okay that AI doesn't really understand what 'things' are. What *really* is a 'chair' or 'water bottle'? What's important is that it can recognize a 'thing' if seen or described.
- It would be great for the AI to understand 'numbers', but it doesn't need to understand 'letters', at first.
- CSV vs JSON. Json is likely better since new fields can be easily added and labeled for readability, and order wouldn't matter. NoSQL.
- Adding definition to words may just be helpful for understanding the AI. The AI wouldn't understand definitions, but may be able to create a knowledge tree from that, but would likely just be parroting. Maybe that's all the output if AI... Just echos of input combined in different ways.
    - Low priority: Teach about common English sentence structure, and common Japanese structure.
- Teach about code. Get it to generate apps or app templates. App templates from a paragraph describing it? "Ability to sign in, but not required" "Settings page with ability to toggle light/dark mode" "using a color theme with black and red" "similar to Google Keep" "the Google for cars" "the Google for cars".
- Start in a small, focused are and excel there. Help me be more awesome. "Ability to show wifi info". All this code in JSON or pointing to a Kotlin file. "Bare bones Hello World app" "ability to track Bitcoin (crypto) prices (on a chart)".
- Feature: Create a 6-word story, option to specify fiction vs non-fiction vs fantasy vs sci-fi vs history vs sports vs cars vs robots/AI.
- Feature: Create 2D pixelated faces, or animals, or sports, or history.
- Feature: Convert random trending [feel-good] Reddit posts to 'full-length' news articles, like Bored Panda
- Give DanAI a set of tools that it can use. Define inputs and outputs. Think of this AI as a small child or dog.

Ideas for learning:
- Go through kindergarten (or pre-K) learning materials
- Possibly use animal training techniques
- Look into dictionaries, fact books, Anki

Open questions:
- How to teach 'numbers', the 'set of numbers', and adding/subtracting? 
- How to teach about multiple definitions of words depending on context
- How to teach 'colors' and its different representations (RGB, CMKY, hue, saturation, brightness)? This AI will start without vision.

# 'tags' = 'context'
axioms: {
  # default tags: 'non-fiction'
  '1 + 1': {
    outputs: { '2' }
    tags: { 'math' }
  }
  'planet we live on': { 
    outputs: { 'Earth' }
    tags: { 'science' }
  }
  'USA president Barack Obama years in office': {
    outputs: { '8 years', '2009-01-20 to 2017-01-20' }
    tags: { 'history' }
  }
  'plum-raisin model for atoms' {
    outputs: { '', <image> }
    tags: { 'science', 'paradigm' }
  }
}
    
sets: {
  'movies'
  'songs': {
    each: { title, artist, lyrics, other metadata }  
  }
  'TV shows'
  'USA presidents': { ... }
}

groupings or components: {
  shoe: { laces, sole, heel, body }
}

definitions: {
  'bottle': ''
  'drink': ''
  'tv': 'television'
  'water': ''
  'water bottle': 'a bottle to drink water from'
}
