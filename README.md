# SortWiz - A data sorting visualizer made using C++ and SDL2

# Introduction
This project is a **Data Sorting Visualizer** implemented in C++ using the SDL2 library. The visualizer provides a graphical representation of various sorting algorithms, offering an intuitive understanding of their mechanics and performance. It's designed as an educational tool for students and enthusiasts to learn and compare sorting algorithms in a visually engaging way.

# Technologies Used
- **C++:** The core programming language used for implementing the logic of sorting algorithms and managing the graphical user interface.
- **SDL2:** A cross-platform development library designed to provide low-level access to audio, keyboard, mouse, joystick, and graphics hardware via OpenGL and Direct3D. It's used here to render the sorting process and handle user inputs.

# Features
- **Multiple Sorting Algorithms:** Includes popular sorting algorithms like Selection Sort, Insertion Sort, Bubble Sort, Merge Sort, Quick Sort, and Heap Sort.
- **Interactive Visualization:** Each sorting algorithm is visualized in real-time, allowing users to see how each element is compared and swapped.
- **Control Menu:** Users can interact with the visualizer, select different sorting algorithms, and randomize the data set.
- **Array Management:** Users can generate a randomized list of numbers which will then be sorted using the selected algorithm.
- **File Handling for Array Datasets:** This feature allows users to load arrays from external files, enabling the visualization of predefined datasets.

# Challenges Faced
- **Performance Optimization:** Ensuring the visualization is smooth and responsive, especially when dealing with large datasets.
- **SDL2 Integration:** Effectively integrating SDL2 with C++ for graphical representation and real-time updates is complex due as the documentation is quite complex
- **User Interaction Design:** Creating an intuitive user interface that's easy to navigate and use.

# Future Prospects
- **Algorithm Customization:** Allow users to tweak algorithm parameters to understand their impact.
- **Comparative Analysis:** Implement features to compare the performance of different sorting algorithms side by side.
- **Extended Support for Larger Datasets:** Optimizing the visualizer to handle larger datasets without compromising on performance.
- **Interactive Learning Module:** Integrate an educational component that explains each step of the sorting process.
