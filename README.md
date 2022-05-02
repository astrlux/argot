# Argot

argot (noun): the jargon or slang of a particular group or class.

## Who's this for?

Do you frequently write technical documentation in Vim with `set spell spelllang=<...>` and suffer "spelling errors" which aren't actually spelling errors? There's no reason why we can't create a spellfile (see `:h 'spellfile'`) that's full of domain-specific jargon so we don't have to keep manually adding words that should already be present in a spellfile for, let's say, software engineers as one example:

> e.g. "memcache", "NeuralNet", "softmax", "CNNs", "MongoDB", "PostgreSQL", etc.

## Usage

```
cd ~/.config/nvim/spell/ && wget https://github.com/astrlux/argot/blob/master/en.MLandAI.utf-8.add
```
