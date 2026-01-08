# My C++ Application

## Overview
This project is a simple C++ application that demonstrates the structure and organization of a C++ project. It includes source files, header files, and unit tests.

## Project Structure
```
my-cpp-app
├── src
│   ├── main.cpp        # Entry point of the application
│   └── app.cpp         # Implementation of application functionality
├── include
│   └── app.hpp         # Header file declaring classes and functions
├── tests
│   └── test_app.cpp    # Unit tests for the application
├── CMakeLists.txt      # CMake configuration file
├── Makefile             # Makefile for building the project
├── .gitignore           # Git ignore file
└── README.md            # Project documentation
```

## Building the Project
To build the project, you can use either CMake or Make.

### Using CMake
1. Create a build directory:
   ```
   mkdir build
   cd build
   ```
2. Run CMake to configure the project:
   ```
   cmake ..
   ```
3. Build the project:
   ```
   make
   ```

### Using Make
Simply run the following command in the project root:
```
make
```

## Running the Application
After building the project, you can run the application using:
```
./my-cpp-app
```

## Running Tests
To run the unit tests, you can execute the following command:
```
./tests/test_app
```

## Contributing
Feel free to fork the repository and submit pull requests for any improvements or bug fixes.

## License
This project is licensed under the MIT License. See the LICENSE file for details.