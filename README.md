# Password-Strength-Checker
Python-based password strength checker. It evaluates passwords based on several security criteria, such as length, the inclusion of numbers, special characters, and both uppercase and lowercase letters. This tool serves as a basic demonstration of password security principles in the realm of cybersecurity.

Here’s a simple implementation of a password strength checker:
Start with the password input.
Check the password length:
If it’s less than 8 characters, output “Weak.”
If the length is between 8 and 12 characters, output “Medium.”
If the length is 12 or more characters, output “Strong.”
Regardless of the length, count the occurrences of uppercase letters, lowercase letters, numbers, and symbols.
If the total count of these characters is less than 3, reduce the strength to “Weak.”
Determine the final strength based on length and character types.
Output the password strength.
