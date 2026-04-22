# Image Editor (C++)

Console-based image processing application developed as an Object-Oriented Programming project.  
The project demonstrates practical C++ skills through implementing core image manipulation filters and file-based workflows.

## Project Highlights
- Built a menu-driven image editor in C++ for loading, processing, and saving images.
- Implemented multiple reusable image-processing operations on top of `stb_image` and `stb_image_write`.
- Applied OOP and modular design principles to keep filter logic organized and extensible.
- Collaborated in a team environment using Git/GitHub for shared development.

## Implemented Features
- Invert colors
- Rotate image (90, 180, 270)
- Convert to black and white
- Convert to grayscale
- Flip image (horizontal/vertical)
- Merge two images
- Add frame (simple and decorated)
- Blur image
- Resize image
- Darken/Lighten image
- Edge detection

## Tech Stack
- Language: C++
- Libraries: `stb_image.h`, `stb_image_write.h`, custom `Image_Class.h`
- Interface: Console (menu-based CLI)

## Repository Structure
- `main.cpp` - Main menu and filter execution flow
- `Image_Class.h` - Image abstraction and utility methods
- `stb_image.h` / `stb_image_write.h` - Image loading/saving back-end

## Build and Run
Compile:
```bash
g++ main.cpp -o main.exe
```

Run:
```bash
./main.exe
```

## Learning Outcomes
- Strengthened C++ problem-solving and memory/data handling fundamentals.
- Gained hands-on experience with classic image-processing techniques.
- Improved team collaboration through version control and code integration.

## Notes
- This project was originally developed as an academic assignment and can be showcased as an early portfolio project in a CV.
