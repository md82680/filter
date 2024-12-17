# Image Filter Program

## Description
This program applies filters to BMP images. It's a C program that can manipulate images by applying various filters to them.

## Features
- Applies image filtering algorithms to BMP files
- Supports multiple filter types
- Command-line interface

## Requirements
- C compiler (clang)
- Make utility
- Input images must be in BMP format

## Compilation
To compile the program:
```

bash
make filter
```

## Usage
To use the program:
```
./filter [filter flag] infile outfile
```

### Example
```
./filter -g ./images/stadium.bmp ./images/stadium-grayscale.bmp
```

## Project Structure
- `filter.c`: Main program file
- `helpers.c`: Filter implementation functions
- `helpers.h`: Header file with function declarations
- `Makefile`: Compilation instructions
- `images/`: Directory containing sample BMP files


## Author
Michael Despo

## Acknowledgments
Based on CS50's Filter Less problem set
```
