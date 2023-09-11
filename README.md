# Harvard CS50x Projects 

## Week 1 - C
### Credit/Debit card check

- Week 1 project was to write a code which checks if a card number is either VISA, AMEX or MASTERCARD
- This utilizes Luhns algorithm where:
  
    1. Multiply every other digit by 2, starting with the number’s second-to-last digit, and then add those products’ digits together.
    2. Add the sum to the sum of the digits that weren’t multiplied by 2.
    3. If the total’s last digit is 0 (or, put more formally, if the total modulo 10 is congruent to 0), the number is valid!
    4. Check if the card is either VISA, AMEX or MASTERCARD <br>
      4.1. AMEX - card length = 15 digits, starting digits = 34, 35 <br>
      4.2. VISA - card length = 13, 16 digits, starting digit = 4 <br>
      4.3. MASTERCARD - card length = 16 digits, starting digits = 51,52,53,54,55

## Week 2 - Arrays
### Caesar cipher

- Week 2 project was to create a caesar cipher

    1. The cipher was to ensure that the key given takes in only integer values
    2. It takes in a plaintext and converts it to a ciphertext that can be sent out
    3. The cipher text also had to ensure that the alphabet could be repeated once any values exceed "Z"
