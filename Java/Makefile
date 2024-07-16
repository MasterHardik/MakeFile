# Define the Java compiler
JC = javac

# Get all Java source files in the current directory
SRCS = $(wildcard *.java)

# Define the target class files (derived from source files)
CLASSES = $(SRCS:.java=.class)

# Default target: compile all Java source files to class files
all: $(CLASSES)

# Target to compile Java source files
%.class: %.java
	$(JC) $<

# Target to clean up generated .class files
clean:
	rm -f *.class