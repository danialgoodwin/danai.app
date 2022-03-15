# DAN AI

A few ideas for my AI. Not necessarily machine learning.


- AI is a programming language that understands itself
    - 'What is var x'
    - 'Given x, what is y'
- AI doesn't need to start by knowing English
    - It's okay that AI doesn't really understand what 'things' are. What *really* is a 'chair' or 'water bottle'? What's important is that it can recognize a 'thing' if seen or described.
- It would be great for the AI to understand 'numbers', but it doesn't need to understand 'letters', at first.

Ideas for learning:
- Go through kindergarten (or pre-K) learning materials
- Possibly use animal training techniques
- Look into dictionaries, fact books, Anki

Open questions:
- How to teach 'numbers', the 'set of numbers', and adding/subtracting? 
- How to teach about multiple definitions of words depending on context

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
  'USA presidents': { ... }
  'TV shows'
}

definitions: {
  'bottle': ''
  'drink': ''
  'water': ''
  'water bottle': 'a bottle to drink water from'
}
