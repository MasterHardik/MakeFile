# Define the C++ compiler
CXX = g++

# Get all C++ source files in the current directory
SRCS = $(wildcard *.cpp)

# Define the target object files (derived from source files)
OBJS = $(SRCS:.cpp=.o)

# Define the target executable file
TARGET = run-app

# Default target: compile all C++ source files to object files and link
all: $(TARGET)

# Target to link object files into executable
$(TARGET): $(OBJS)
	$(CXX) $^ -o $@

# Target to compile C++ source files into object files
%.o: %.cpp
	$(CXX) -c $< -o $@

# Target to clean up generated object and executable files
clean:
	rm -f $(OBJS) $(TARGET) *.exe
