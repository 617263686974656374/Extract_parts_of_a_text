# Extract_parts_of_a_text
This tool is straightforward and useful for situations where information needs to be quickly extracted from structured text, such as processing formatted logs, data entries, or simple structured communications.

**Description:**

This Java program is designed to extract specific information from a structured text input provided by the user. It specifically parses strings that describe an item and the customer who ordered it, formatted in a predetermined way.

**Functionality:**

- The program prompts the user to enter text in a specific format: `theItem[Item]wasOrderedBy[Customer]`.
- It then extracts the item name and the customer name from the provided string.
- The extracted names of the item and customer are then displayed to the user.
- The program includes error handling to guide the user to input the text in the correct format if the initial attempt fails.

**Usage:**

1. Run the program.
2. Enter a string following the specified format: `theItem[Item]wasOrderedBy[Customer]`.
3. The program will output the names of the item and the customer extracted from the string.
4. If the format is incorrect, an error message will be displayed, prompting the user to re-enter the string correctly.

**Example:**

- Input: `theItem[Laptop]wasOrderedBy[John Doe]`
- Output:
  - Item: Laptop
  - Customer: John Doe

**Error Handling:**

- The program ensures that the input follows the expected format.
- In case of any deviations or parsing errors, it instructs the user to input the string correctly, showing a helpful error message.
