# PasswordGenerator
GIVEN I need a new, secure password
I am presented with a series of inputs for password criteria
THEN I select which criteria to include in the password
WHEN prompted for the length of the password
THEN I choose a length of at least 8 characters and no more than 128 characters
WHEN prompted for character types to include in the password
THEN I choose lowercase, uppercase, numeric, and/or special characters
THEN my input should be validated and at least one character type should be selected
WHEN all criteria are answered
THEN a password is generated that matches the selected criteria
WHEN the password is generated
THEN the password is written to the page