# colorset-generator

## What is this?

This script processes the XKCD color dataset available at [https://xkcd.com/color/rgb/](https://xkcd.com/color/rgb/) and outputs a filtered list of colors based on the number of words in their names. 

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/kamranvat/colorset-generator.git
cd colorset-generator
```

## Usage

1. Run the script:

    ```bash
    python generate.py
    ```

2. Follow the prompts to input the parameters:
   - Maximum number of words for colors (e.g. 1 to include "green", but to exclude "dark green").
   - Output format \(csv, txt, json\).
   - Color format \(hex, rgb\).

3. The filtered color list will be saved in the `./output` directory.

## Known Issues

This tool has been built for a single, specific use-case.
- The script requires specific input, and any deviation may result in unexpected behavior.
- Limited testing has been performed, and there may be undiscovered issues.
