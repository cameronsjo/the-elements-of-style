# The Elements of Style

William Strunk Jr.'s *The Elements of Style* (1918) as a Claude Code reference skill for clear, precise writing.

> Maintained fork of [obra/the-elements-of-style](https://github.com/obra/the-elements-of-style) by [@cameronsjo](https://github.com/cameronsjo).

Gives Claude access to Strunk's foundational writing guidance when working on documentation, user-facing text, or any prose that needs clarity and proper style.

## What's Inside

The plugin provides:

- **Skill**: `writing-clearly-and-concisely` - Guidance on when and how to use Strunk's rules
- **Reference**: Complete 1918 text with all rules, examples, and usage guidance (~12,000 tokens)

The reference contains:

1. **Elementary Rules of Usage** - Seven fundamental grammar and punctuation rules
2. **Elementary Principles of Composition** - Eleven rules for clear, effective writing
3. **Words and Expressions Commonly Misused** - An alphabetical guide to usage pitfalls

## Usage

Once installed, Claude will automatically use the `writing-clearly-and-concisely` skill when appropriate. The skill:

- Warns about the 12,000-token reference size
- Lists all rules at a glance
- Suggests dispatching a subagent for copyediting when context is limited
- Only loads the full reference when actively writing or editing prose

## Source

Public domain. Original 1918 edition from [Project Gutenberg #37134](https://www.gutenberg.org/files/37134/37134-h/37134-h.htm), converted to markdown.

## Support

- **Issues**: https://github.com/cameronsjo/the-elements-of-style/issues
- **Upstream**: https://github.com/obra/the-elements-of-style
