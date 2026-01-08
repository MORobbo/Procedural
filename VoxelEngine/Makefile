CC = g++
CFLAGS = -Iinclude -Wall -Wextra -std=c++17
SRC = src/main.cpp src/app.cpp
OBJ = $(SRC:.cpp=.o)
TARGET = my_cpp_app

all: $(TARGET)

$(TARGET): $(OBJ)
	$(CC) -o $@ $^

%.o: %.cpp
	$(CC) $(CFLAGS) -c $< -o $@

clean:
	rm -f $(OBJ) $(TARGET)

.PHONY: all clean