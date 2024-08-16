# BMP File Bottom-Up to Top-Down Converter

## Description
This project is a BMP file converter written in C. It reads an input BMP file, flips the image from bottom-up to top-down, and writes the flipped image to an output BMP file. The project incorporates the `bmp.h` file for BMP-related data types based on Microsoft's specifications.

## Features
- Convert BMP files from bottom-up to top-down - *I myself did not create the BMP.h file used in this Project, but utilized contents for demo of code*
- Ensure proper usage and file format validation
- Allocate memory for image processing

## Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/image-top-bottom.git
   ```
2. Navigate to the project directory:
   ```bash
   cd bmp-bottomup-converter
   ```
3. Compile the code:
   ```bash
   make bottomup
   ```

## Usage
1. Run the application:
   ```bash
   ./bottomup infile outfile
   ```
   Replace `infile` with the path to the input BMP file and `outfile` with the path to the output BMP file.

## Example
```bash
$ ./bottomup input.bmp output.bmp
```

## Contributing
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature/your-feature-name
   ```
3. Make your changes and commit them:
   ```bash
   git commit -m 'Add some feature'
   ```
4. Push to the branch:
   ```bash
   git push origin feature/your-feature-name
   ```
5. Open a pull request.

## License
This project is not licensed under any License currently.
