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

![image](https://github.com/user-attachments/assets/343daf3f-bb66-42c0-a6cf-284835395ea2)

![image](https://github.com/user-attachments/assets/2323a7c3-1430-4d24-a88e-27dac7342c42)
![image](https://github.com/user-attachments/assets/d22f4aca-0db1-4adc-8803-003d24841503)
*Before!*

![image](https://github.com/user-attachments/assets/2ad7154f-9fc5-4067-8d71-7722b4afd820)
![image](https://github.com/user-attachments/assets/9af831af-922f-42e8-ae67-56377ccb3623)
*After! Check it out, whooo!!!*

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
