**Description of global variables**:

*config* - dictionary, storing the application's settings.

*dictRu* - dictionary, storing translation of UI into Russian.

*dictEn* - dictionary, storing the UI translation into English.

*dictDe* - dictionary storing the UI translation into German.

*dictEs* - dictionary storing the UI translation into Spanish.

*dictFr* - dictionary storing the French translation of the UI.

*allDicts* - dictionary, storing dictionaries for the whole set of languages.

*valueInput* - UI element, which stores the value entered by the user.

*resultInput* - UI element, which stores the result value of the square root calculation.

*precisionInput* - UI element, which stores the value of significant digits.

*precisionSlider* - UI element, which is associated with the slider to change the value of significant digits.

*digitsAfterPointInput* - UI element which stores the value of digits after the decimal point.

*digitsAfterPointSlider* - the UI element linked to the slider to change the value of digits after the decimal point.

*languageSelect* - UI element, which stores the currently selected language.

**Function description**:

*clampDigits*

- Description: trims the number of digits after the decimal point for the output to the specified
- Input parameters:
  - *value* - number for which the number of decimal places is set

*clamp*

- Description: limits the number of digits in the specified range
- Input parameters:
  - *precision* - number
  - *min* - minimum value
  - *max* - maximum value

*setPrecision*

- Description: sets the accuracy value for the result number 
- Input parameters:
  - *precision* - accuracy value

*setDigitsAfterPoint*

- Description: Sets the number of decimal places for the resultant number 
- Input parameters:
  - *digits* - value of the number of decimal places

*setPrecisionSupported*

- Description: sets the precision support depending on the value of the value flag 
- Input parameters:
  - *value* - the logical value of the flag

*updateResult*

- Description: calculates the square root value and updates the value of the output variable

*updateLanguage*

- Description: updates the text description of the UI elements when the language changes