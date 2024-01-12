# CSSify - CSS Class Generator

The CSS Class Generator is a simple web application built with HTML, CSS, and JavaScript. The purpose of this tool is to facilitate the generation of CSS class rules based on user input. It supports the creation of both regular class rules (starting with `.`) and ID rules (starting with `#`).

## Features

### 1. Input Instructions

* The application provides a clear input label with a tooltip for guidance.
* Users can enter their classes either on a new line or separated by commas.

### 2. Class Generation

* The tool processes the input and generates corresponding CSS class rules.
    
* For each entered class, it creates a CSS rule in the format:
    
    ```css
    .className {
    
    }
    ```
    
    or
    
    ```css
    #className {
    
    }
    ```
    
    based on whether the class name ends with a hyphen (`-`).
    

### 3. Copy to Clipboard

* Users can copy all generated CSS rules to the clipboard with the click of a button.
* A "Copy CSS" button becomes visible when CSS rules are generated.

### 4. Notification

* After copying to the clipboard, a notification appears at the top, informing the user that all CSS rules have been successfully copied. The notification disappears after 3 seconds.

### 5. Clear Button

* The user can clear the input field and generated CSS rules with a "Clear" button.

### 6. Code Colorization

* The generated CSS rules in the output area are colorized for better readability.

### 7. User Instructions

* Users can click on the "Enter classes:" label to toggle instructions on how to enter classes.

## Usage

1. **Enter Classes:**
    
    * Start by entering your classes in the provided textarea. You can input them either on a new line or separated by commas.
        
    * Example:
        
        ```plaintext
        classOne
        classTwo-
        classThree
        ```
        
        or
        
        ```plaintext
        classOne, classTwo-, classThree
        ```
        
2. **Generate CSS:**
    
    * Click the "Generate CSS" button to create CSS rules based on the entered classes.
3. **Copy to Clipboard:**
    
    * Once CSS rules are generated, the "Copy CSS" button becomes visible.
    * Click on the "Copy CSS" button to copy all generated CSS rules to the clipboard.
4. **Notification:**
    
    * After copying, a notification appears, indicating the successful copying of CSS rules. The notification disappears after 3 seconds.
5. **Clear Input:**
    
    * Use the "Clear" button to reset the input field and clear the generated CSS rules.
6. **Toggle Instructions:**
    
    * Click on the "Enter classes:" label to toggle instructions on how to enter classes.