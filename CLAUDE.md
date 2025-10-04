# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a series of interactive games designed for kids. The games are built collaboratively with children in classroom settings, where kids vote on features and game mechanics they want to implement.

## Architecture

- **Single HTML Files**: Each game is a self-contained HTML file with embedded CSS and JavaScript
- **Click-Based Mechanics**: Games use simple click/tap interactions suitable for children
- **Visual Effects**: Heavy use of CSS animations, emojis, and colorful feedback (sparkles, confetti, floating text)
- **No External Dependencies**: Games run directly in browsers without frameworks or external libraries

## Content Guidelines

### Age-Appropriate Content
- **Target Audience**: Children (around 9 years old)
- **Violence Level**: Minimal violence acceptable (e.g., "shooting" at friendly ghosts, catching robots)
- **Themes**: Use friendly, colorful, and playful elements
- **Visual Style**: Bright colors, emojis, fun animations

### Technical Simplicity
- Keep game mechanics simple and intuitive
- If a requested feature seems too complex, offer simpler alternatives
- Prioritize working games over complex features
- Use clear, readable code structure

## Development Approach

### Be Proactive
- Offer creative alternatives when kids suggest features
- Suggest improvements to make games more engaging
- Provide multiple options when possible to facilitate voting

### Classroom Context
- The user will be presenting to a class of children
- Kids will vote on features and directions
- Be prepared to explain why something might be too complex and offer simpler alternatives
- Focus on features that can be implemented quickly and demonstrated immediately

## Common Game Patterns

1. **Score Systems**: Simple counters with visual feedback
2. **Moving Targets**: Elements that change position periodically
3. **Click Effects**: Immediate visual feedback (animations, particle effects)
4. **Emoji Characters**: Use emojis as game sprites (👻, 🤖, 🚗, ⭐)
5. **Color Changes**: Dynamic color schemes for engagement

## Technical Stack

- **HTML5** with semantic structure
- **CSS3** with animations and gradients
- **Vanilla JavaScript** (no frameworks)
- **Emoji Unicode** for characters and effects