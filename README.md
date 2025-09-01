\# 3D Graphics Renderer



\*\*Status:\*\* Ongoing



A C++ project for processing 3D vertex input data to construct and display polyhedra images using a bottom-up graphics pipeline.



---



\## Project Overview



This project explores the fundamental principles of 3D graphics programming, computational geometry, and linear algebra by building a rendering engine from scratch. It emphasizes understanding low-level mechanics rather than relying entirely on high-level graphics libraries. OpenGL is used only to display the final 2D image.



---



\## Goals



\- Develop a robust, bottom-up understanding of 3D graphics rendering

\- Implement core vector and matrix operations for transformations, projections, and lighting

\- Build a modular system architecture that can be expanded to support additional rendering techniques

\- Showcase proficiency in C++17 features including object-oriented design, templates, and memory management

\- Demonstrate technical depth through practical application of mathematics in programming



---



\## Objectives



\- Implement classes and functions for core vector math operations (dot product, cross product, vector normalization)

\- Parse and handle 3D vertex input data efficiently

\- Construct polyhedra using vertex and face definitions

\- Apply transformations: translation, scaling, rotation, and project 3D coordinates to 2D

\- Implement a basic lighting and shading model for realistic rendering

\- Provide clear documentation and modular code to facilitate future extensions, e.g., camera control or texture mapping



---



\## Highlights



\- Bottom-up rendering pipeline built from scratch

\- Strong emphasis on computational geometry and linear algebra

\- Modular, readable, and maintainable C++ code structure

\- Ability to translate mathematical concepts into practical graphics applications



---



\## Build / Run



Requires a C++17-compatible compiler. Example compilation commands:



```bash

g++ -std=c++17 main.cpp Polyhedron.cpp -o renderer

./renderer



