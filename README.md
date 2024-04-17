# Traffic-Light-using-Swing

This project is a simple traffic light simulation implemented in Java using Swing for the graphical user interface. The simulation displays a traffic light with three colors: red, yellow, and green. Users can manually control the traffic light by selecting the desired color.

## Features

- Graphical representation of a traffic light with three colors: red, yellow, and green.
- User can manually control the traffic light by selecting the desired color.

## How to Run

1. Ensure you have Java installed on your machine. You can download it from [here](https://www.oracle.com/java/technologies/javase-jdk11-downloads.html).
2. Clone this repository to your local machine.
3. Navigate to the directory where you cloned the repository.
4. Compile the Java file using the command: `javac src/traffic.java`.
5. Run the compiled Java file using the command: `java src/traffic`.

## Code Structure

The project consists of two classes:

- `trafficlight`: This class represents the traffic light. It extends `JPanel` and implements `ActionListener`. It contains three `JRadioButton` objects representing the three colors of the traffic light. The `paintComponent` method is overridden to draw the traffic light, and the `actionPerformed` method is overridden to handle the radio button selection events.

- `traffic`: This class contains the `main` method which creates a `JFrame` and adds an instance of `trafficlight` to it.

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
