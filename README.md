# Argot

argot (noun): the jargon or slang of a particular group or class.

### Who's this for?

Do you frequently write technical documentation in Vim with `set spell spelllang=<...>` and suffer "spelling errors" which aren't actually spelling errors? There's no reason why we can't create a spellfile (see `:h 'spellfile'`) that's full of domain-specific jargon so we don't have to keep manually adding words that should already be present in a spellfile for, let's say, software engineers as one example:

> e.g. "memcache", "NeuralNet", "softmax", "CNNs", "MongoDB", "PostgreSQL", etc.

Important words being incorrectly marked as spelling mistakes are super distracting, so a no-bloat solution entails simply using domain specific `spellfiles`.

## Usage

Only minimal work on your end, unless you want to contribute to actually make this tool something that people like us can use to improve their workflow. Navigate to the directory where spellfiles are kept (`~/.config/nvim/spell/`).
