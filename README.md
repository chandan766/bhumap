## Land Measurement Unit Conversion Tool

The given HTML program creates a web-based tool for converting various land measurement units. Users can input a value in one unit, choose another unit for conversion, and the program will calculate and display the converted value. This program also allows users to customize and save conversion factors for different units using a modal dialog.
![Screenshot 2023-08-21 104613](https://github.com/cr3992/bhumap/assets/76623223/8f948401-b32b-4642-8415-2adb3dda60b5)
### Header and Styling

The program includes links to external CSS and JavaScript libraries (Bootstrap and Font Awesome) to enhance styling and functionality.

### Header Section

The title "भूमि मापन इकाइयाँ" (Land Measurement Units) is displayed on a colored background.

### Unit Selection and Conversion Interface

- Two dropdown menus offer options for different land measurement units such as "हेक्टेयर," "एकड़," "एयर," etc.
- Users select units for conversion in these dropdowns: one as the input unit and the other as the desired output unit.
- Two input fields are available: one for entering the value in the input unit and another for displaying the converted value in the output unit.
- As users input a value, the program automatically performs the conversion and updates the output field.

### Unit Conversion Logic

- JavaScript functions in the program handle conversion calculations for each pair of units.
- Conversion factors are derived from default values or user-defined values if previously saved.

### Modal Dialog for Custom Conversion Factors

- Clicking the "मानक पैमाना" (Standard Measurement) button triggers a modal dialog to appear.
- The modal dialog contains a grid with input fields for each unit, allowing users to customize conversion factors.
- Users can modify these factors and save them using the "Save" button.
- A "reset" button clears saved customizations, restoring default values.

### JavaScript Functions

The JavaScript section contains functions for:
- Conversion calculations
- Unit selection changes
- Interchanging units
- Loading saved values
- Saving custom values
- Clearing saved values

### Styling

Custom CSS styles are applied to various elements, including input fields, buttons, and the modal dialog.

### User Interaction

Users interact with the program by selecting units, entering values, and viewing converted results. They can also customize conversion factors through the modal dialog and save or reset these customizations.
