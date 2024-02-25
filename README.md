

# Icon Color Changer

## Description

This Python script changes the color of all non-transparent pixels in PNG icons to a specified color. It's designed to process a batch of icons in a directory, applying the color transformation to each icon and saving the modified versions in the same location or a different one.

## Features

- Batch processing of PNG icons.
- Changes non-transparent pixels to a specified color while preserving the icon's transparency.
- Customizable input and output directories.

## Requirements

- Python 3.x
- Pillow library

## Installation

Before running the script, ensure you have Python 3.x installed on your system. You can download Python from [the official website](https://www.python.org/downloads/).

Install the Pillow library using pip:

```bash
pip install Pillow
```

## Usage

1. **Set Up Directories**: Modify the `input_dir` and `output_dir` variables in the script to point to your icons' directory and the desired output directory, respectively.

2. **Specify the New Color**: Set the `hex_color` variable to the hex code of the color you want to apply to the icons. The default is set to `#1fd902`.

3. **Run the Script**: Execute the script with Python.

```bash
python main.py
```

4. **Check the Output**: The modified icons will be saved in the specified output directory.

## Customization

- **Change Color**: Modify the `hex_color` variable in the script to change the color applied to the icons.
- **Change Directories**: Adjust the `input_dir` and `output_dir` variables to point to the correct directories on your system.

## Contributions

Contributions to this project are welcome. Please fork the repository and submit a pull request with your improvements.

## License

This project is open-sourced under the MIT License. See the LICENSE file for more details.
