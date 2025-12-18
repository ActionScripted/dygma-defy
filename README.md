# Dygma Defy Keyboard Layout

Custom keyboard layout for the **Dygma Defy**. This configuration is optimized for efficient typing and development workflow, with dedicated layers for symbols, functional keys, and advanced features.

## Configuration Files

- [**backup-automatic.json**](backup-automatic.json) - Automatic backup created by Bazecor
- [**backup-manual.json**](backup-manual.json) - Manual backup exported from Bazecor settings

## Layout Overview

This layout prioritizes **ergonomics over speed** and has been optimized for **macOS**, **Neovim**, and **shell** work. It minimizes weak finger usage and lateral movement by keeping outer columns inactive while remaining approachable for those used to standard QWERTY.

Thumb clusters are mirrored and handle layers, modifiers, and actions to avoid awkward hand contortions. Use both hands when holding modifiers: one thumb on the modifier, the other hand hitting the key. This also lets you use the mouse (or trackball!) with one hand.

Symbols are organized by logical relationships. Openers and closers group together -- parentheses with brackets with braces. Related symbols cluster by function: math operators in one spot, comparisons in another, comments together.

**Physical modification:** Quote keycap was moved one left to replace colon/semicolon (absent from the base layer) and a blank was placed where the quote cap was. This suits my needs but may need adjustment depending what languages you use.

## Layer 1: Base

Standard QWERTY layout with quote shifted one position left and colon/semicolon relocated off the base layer.

**Thumbs:** Tap/hold keys for ctrl/tab, shift/backspace, cmd/space, opt/enter, ctrl/esc (left outer), colon (right outer). Layer holds to access layers 2, 3, 4.

[![Base Layer](layer1_base.png)](layer1_base.png)

## Layer 2: Symbols

Programming symbols organized by logical groupings (openers/closers, math operators, comparisons, comments), with markdown and directory navigation shortcuts accessible on the thumbs.

**Thumbs:** Backtick, tilde, slash (other thumb keys transparent to layer 1).

[![Symbols Layer](layer2_symbols.png)](layer2_symbols.png)

## Layer 3: Functional

**Left side:** F-keys, media controls, show desktop, copy menu, emoji menu, window/tab switching.

**Right side:** Character and word-level backspace/delete, arrow keys, line navigation (start/end, word left/right), page up/down, home/end.

**Thumbs:** All transparent to layer 1.

[![Functional Layer](layer3_functional.png)](layer3_functional.png)

## Layer 4: Magic

**Left side:** Lock screen, sound settings, show/hide dock, screenshot, battery level, LED brightness and color changes.

**Right side:** Mouse movement, mouse wheel, mouse buttons.

**Thumbs:** All transparent to layer 1.

[![Magic Layer](layer4_magic.png)](layer4_magic.png)

## Layer 5+: ???

These are either me abusing layers to move things around, back things up or play with some stuff like maybe having a gaming layer. Rough stuff above layer 4, just ignore these.

## Rough Edges

I still don't love two-hands for some things. Cmd + Tab for example sucks two hands and isn't fun with this layout with one hand and it feels super wonky if you're used to using it a lot.

The thumbs can be confusing and hitting enter when chatting when you meant to send a space or delete can be annoying at first. Some textured mouse rubber can be a nice addition to some of the thumb keys to help you know where you are and what you're hitting.

Have tried super keys and the timing of them just continues to annoy the crap out of me so we're not really using them. Haven't tried the new updated super keys though.

I need repeats on home row keys so home row mods weren't ideal for me but I love the idea of home row stuff and less thumb stuff for some actions (maybe cmd and tab...).

## Restoring Defaults

To restore your keyboard to factory settings or learn how to load these backup configurations, see the official guide: [how to restore the default configuration of the keyboard](https://support.dygma.com/hc/en-us/articles/360007165377-How-to-restore-the-default-configuration-of-the-keyboard).
