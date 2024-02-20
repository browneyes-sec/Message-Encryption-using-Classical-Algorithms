# Message-Encryption-using-Classical-Algorithms
Author: José Pablo Molina Ávila
Classic encryption algorithms, like Caesar and Vigenère ciphers, use basic mathematical principles for message security, despite vulnerability to modern techniques.

Classic encryption algorithms refer to cryptographic techniques developed and used over a long period, often before the widespread adoption of computers. These algorithms are typically characterized by their simplicity, reliance on mathematical principles, and historical significance. Some of the most well-known classic encryption algorithms include:

The C++ code present in this repository is provided in a text (.txt) format and intended to be shared for educational purposes. For practical comprehension, download the text file and compile it. The instructions are in Spanish, use a translator to solve the language gap.

1. **Caesar Cipher**: Named after Julius Caesar, this is one of the earliest known substitution ciphers. It involves shifting each letter of the plaintext by a fixed number of positions in the alphabet.

2. **Vigenère Cipher**: Developed in the 16th century, this polyalphabetic substitution cipher uses a keyword to determine the shift applied to each letter in the plaintext, making it more resistant to frequency analysis compared to simple substitution ciphers.

3. **Transposition Cipher**: This type of cipher involves rearranging the order of characters in the plaintext to create the ciphertext. Examples include the Rail Fence cipher and the Columnar Transposition cipher.

4. **Vernam Cipher**: The Vernam Cipher, also known as the one-time pad, is an encryption method that uses a random key that is at least as long as the message itself. A theoretically unbreakable encryption technique, the one-time pad involves using a random key that is at least as long as the plaintext. Each key is used only once, providing perfect secrecy if used correctly.

5. **Binary to Decimal and Vice Versa:**
Binary-to-decimal conversion involves transforming a binary number (base-2) into its equivalent decimal representation (base-10) by multiplying each binary digit by its corresponding power of 2 and summing the results. For example, the binary number 1011 is converted to decimal as follows: 

(1 * 2^3) + (0 * 2^2) + (1 * 2^1) + (1 * 2^0) = 8 + 0 + 2 + 1 = 11.

Decimal to binary conversion entails dividing the decimal number by 2 successively and noting the remainder. Reading these remainders from bottom to top gives the binary representation. For example, to convert decimal 11 to binary:

11 ÷ 2 = 5 remainder 1
5 ÷ 2 = 2 remainder 1
2 ÷ 2 = 1 remainder 0
1 ÷ 2 = 0 remainder 1

Reading the remainder from bottom to top gives 1011.

6. **Dictionary Cipher**: The dictionary cipher is a simple substitution cipher where each letter in the plaintext is replaced by a corresponding word from a pre-agreed dictionary. For example, if "apple" represents the letter "a", "banana" represents "b", and so on, then the word "banana apple" could represent the string "ba". This method can enhance security by making frequency analysis more difficult, but it requires a shared dictionary between sender and receiver and can be vulnerable if the dictionary falls into the wrong hands.

7. **Summing bits**: Summing bits involves adding corresponding bits from two binary numbers together, bit by bit, similar to how you add decimal digits in regular addition. This method is particularly useful in digital logic circuits, computer arithmetic, and cryptography.

Classic encryption algorithms are often no longer used for securing sensitive information due to their vulnerability to modern cryptanalysis techniques. However, they remain significant in the history of cryptography and are still studied for educational and historical purposes.
