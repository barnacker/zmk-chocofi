# SynthX Keyboard Layout
A custom keyboard layout optimized for split ortholinear keyboards, designed for comfortable and efficient typing on boards like the Corne (Chocofi).

## Layout Overview

SynthX is a custom alpha layout that prioritizes home row comfort and logical symbol placement for programming and general typing.

### Alpha Keys

```
F B K L J     = W ' / .
S N T H V     G C A E I
X P D M Q     Z Y O U ,
```
<img width="1273" height="603" alt="image" src="https://github.com/user-attachments/assets/d6f8fb27-b85e-417d-80f9-66e61f1a9836" />

### Key Features

- **Home Row Mods**: GACS on left (GUI, Alt, Ctrl, Shift), SCAG on right
- **Common Punctuation**: Strategic placement of quotes, slashes, and periods on the right side
- **Comfortable Rolls**: Optimized letter combinations for English
- **Split-Friendly**: Designed specifically for column-stagger split keyboards

## Character Mappings

<img width="900" height="2040" alt="my_keymap" src="https://github.com/user-attachments/assets/5486ec71-1abf-47d4-8d2f-0fd895a4a642" />

## Installation

### For ZMK Firmware
See the [ZMK config repository](https://github.com/barnacker/zmk-chocofi) for the complete keymap definition.

### For keybr.com Practice
1. Clone the keybr.com repository
2. Copy `en_synthx.json` to `packages/keybr-generators/layouts/`
3. Add the layout entry to `packages/keybr-generators/lib/generate-layouts.ts`
4. Run the generator: `npx tsx ./lib/generate-layouts.ts`
5. Register the layout in `packages/keybr-keyboard/lib/layout.ts`
6. Add imports to `packages/keybr-keyboard/lib/load.ts`
7. Build and run keybr locally

See [keybr custom keyboard documentation](https://github.com/aradzie/keybr.com/blob/master/docs/custom_keyboard.md) for details.

## Design Philosophy

SynthX was designed with the following principles:

1. **Home Row Optimization**: Most frequent letters placed on the home row
2. **Hand Alternation**: Balanced workload between hands
3. **Common Bigrams**: Frequently typed letter pairs placed for comfortable rolls
4. **Symbol Access**: Programming symbols easily accessible without excessive stretching
5. **Split Ergonomics**: Designed for split keyboards with home row mods

## Learning Resources

- Practice at [keybr.com](https://www.keybr.com) (with custom layout installed)
- [Monkeytype](https://monkeytype.com) (can import custom layouts)
- [TypeFast](https://typefast.io)

## Stats & Metrics

*Add your personal stats here after using the layout*

- Typing Speed: ___ WPM
- Accuracy: ____%
- Learning Time: ___ weeks/months
- SFB (Same Finger Bigrams): ___
- Home Row Usage: ____%

## Comparisons

### vs QWERTY
- Lower same-finger bigrams
- More home row usage
- Better hand alternation

### vs Colemak
- [Your comparison notes]

### vs Dvorak
- [Your comparison notes]

## License

This layout definition is released under the same license as the keybr.com project (GPL-3.0).

## Contributing

Found an improvement or issue? Open an issue or pull request!

## Author

Created by barnacker

---

**Hardware Used**: Corne (Chocofi) with ZMK firmware  
**Version**: 1.0  
**Last Updated**: 2025-10-16

<img width="900" height="2040" alt="my_keymap" src="https://github.com/user-attachments/assets/443fb466-5193-4b68-927c-a4a56856e055" />
