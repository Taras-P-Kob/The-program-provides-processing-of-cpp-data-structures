# C++ Data Structure Processor

## Overview

This program allows you to process and manage data structures efficiently. The example use case involves managing information about **text editors**, with fields such as `name`, `manufacturer`, `license`, `rating`, and `price`. 

The program supports various operations, including:
- Adding new items
- Searching for items by field values
- Viewing all items sequentially
- Modifying item field values
- Deleting items
- Sorting items by specific fields

All operations are logged and saved to a file, ensuring data persistence. The program includes at least ten records to demonstrate functionality.

---

## Features

1. **Add New Items**  
   Easily add new text editor entries with all relevant details.

2. **Search Items**  
   Quickly search for an item by any field, such as name or license.

3. **View Items**  
   Browse all stored text editors in a user-friendly sequential manner.

4. **Edit Items**  
   Update the details of any text editor, including its name, manufacturer, or other fields.

5. **Delete Items**  
   Remove entries from the list seamlessly.

6. **Sort Items**  
   Sort text editors by a specified field, such as license type or price.

7. **File Persistence**  
   All changes are automatically saved to a file for data retention.

---

## Example Use Case: Text Editors

Each text editor is defined by the following attributes:
- **Name**: The name of the text editor (e.g., "Visual Studio Code").
- **Manufacturer**: The company or developer behind the editor (e.g., "Microsoft").
- **License**: The type of license (e.g., "Free", "Proprietary").
- **Rating**: User or community rating (e.g., "4.5").
- **Price**: The cost of the text editor (e.g., "$0" for free editors).

---

## Program Demonstration

### Main Menu
![Main Menu](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/d6cd28cd-ddac-47c7-bc23-5203bd7c93ad)

---

### Viewing All Text Editors
![All Text Editors](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/74982141-c74e-46d0-b8b0-fbb8ef1245d3)

---

### Edit Options
![Edit Option](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/162eeeaf-5978-4f04-8099-5748a592d905)

---

### Adding a New Text Editor
![Adding New Text Editor](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/19925d83-65b3-459c-972d-56c661d86bcf)

---

### Deleting a Text Editor
![Deleting Text Editor](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/c08a7e2e-b864-4770-9fc2-32486e07bfde)

---

### Sorting Example (by License)
![Sorting by License](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/801e50d5-8210-4499-9827-456f34d95a5d)

---

### Searching Example (by Name)
![Searching by Name](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/0d3512cf-7191-455e-b6af-b2601bacaf27)

---

### Exit Option
![Exit Option](https://github.com/Taras-P-Kob/The-program-provides-processing-of-cpp-data-structures/assets/119957094/0d3512cf-7191-455e-b6af-b2601bacaf27)

---

## File Structure

- The program maintains a file that stores all text editor records.
- Changes made via any operation (add, delete, modify) are instantly reflected in the file.

---

## How to Use

1. Clone the repository:
   ```bash
   git clone https://github.com/roman-zvir/text-editors-structure.git
   ```
2. Compile the program:
   ```bash
   g++ -o text-editors main.cpp
   ```
3. Run the executable:
   ```bash
   ./text-editors
   ```

---

## License

This project is open-source and distributed under the [MIT License](LICENSE).
