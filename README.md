# Moroccan Operator Checker
This is a simple web-based application that identifies the Moroccan telecom operator for a given phone number. Users can input a phone number, and the system will determine the operator based on predefined prefixes for Maroc Telecom, Orange Maroc, and inwi.

## Features
- User-friendly interface with HTML, CSS, and JavaScript.
- Validates Moroccan phone numbers.
- Determines the telecom operator based on number prefixes.
- Displays results instantly.

## How It Works
1. The user enters a phone number in the input field (e.g., `061198563412`).
2. The application extracts the first four digits of the number.
3. It compares the extracted prefix against predefined mappings for each operator:
   - **Maroc Telecom**: `0610`, `0611`, `0613`...
   - **Orange Maroc**: `0612`, `0614`, `0617`...
   - **inwi**: `0526`, `0527`, `0533`...
4. The operator name is displayed, or an "Unknown Operator" message is shown if no match is found.

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/taher_el_mehdi/moroccan-operator-checker.git
   ```
2. Open the `index.html` file in a web browser.
3. Enter a valid Moroccan phone number to identify the operator.

## Demo
You can try the application [here](#).

## Contributing
Contributions are welcome! Follow these steps to contribute:
1. Fork the repository.
2. Create a new branch:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes:
   ```bash
   git commit -m "Add new feature"
   ```
4. Push the branch:
   ```bash
   git push origin feature-name
   ```
5. Open a pull request.

## License
This project is open source and available under the [MIT License](LICENSE).

## Contact
For questions or suggestions, feel free to contact me.