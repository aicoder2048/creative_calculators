# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This repository contains a collection of 5 creatively designed web calculators, each with unique visual themes and animations. All calculators are standalone HTML files with embedded CSS and JavaScript - no build process or dependencies required.

## Calculator Files

- `cyberpunk_matrix_calculator.html` - Matrix-style green-on-black terminal aesthetic
- `neumorphic_soft_ui_calculator.html` - Modern soft UI design with depth effects
- `psychedelic_kaleidoscope_calculator.html` - 60s/70s psychedelic art style
- `3d_holographic_cube_calculator.html` - 3D rotating cube with holographic effects
- `dna_helix_bio_calculator.html` - DNA double helix with decimal/hexadecimal modes

## Key Features of DNA Calculator

The DNA calculator is the most complex, featuring:
- **Dual number system support**: Toggle between decimal (0-9) and hexadecimal (0-F) modes
- **Base pair mapping**: Each digit/letter maps to specific DNA base pairs (AT, CG, etc.)
- **Negative number handling**: Displays negative sign separately in genetic sequences
- **Test file**: `hex_comprehensive.html` provides comprehensive testing for hex mode

## Development Commands

```bash
# Run local web server (no build needed)
python3 -m http.server 8080
# or
open [calculator_name].html

# Git operations
git add -A
git commit -m "message"
git push origin main
```

## Architecture Notes

Each calculator follows this pattern:
1. Single HTML file with all code embedded
2. CSS animations and transitions for visual effects
3. JavaScript calculator logic with event handlers
4. No external dependencies or frameworks

The DNA calculator has additional complexity:
- Mode switching logic between decimal/hexadecimal
- Dynamic helix generation based on current mode
- Special visual indicators for hex-only digits (A-F)

## GitHub Repository

Repository: https://github.com/aicoder2048/creative_calculators

Screenshots are stored in `screenshots/` directory but excluded from version control via .gitignore.