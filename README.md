# WEB and API App for Random password Generator

Python Library: https://github.com/suryasr007/random-password-generator
 
## API (GET Request)
 * Base_url: https://random-pg.herokuapp.com
 * Generate simple password ```/api/generate```
   * Optional Attributes can be provided as params  
     eg: 
     ```
      /api/generate?minlen=16  
      /api/generate?minlen=16&minlchars=5
     ```
 * Generate a custom password from givin characters
   * Mandatory attributes can be provided as params  
     eg: 
     ```
      /api/shuffle?password=sdjbfbfB&maxlen=14
     ```
 * Generate a non duplicate password.  
   * Mandatory Attribute 'maxlen'  
     eg:
     ``` 
      /nonduplicate?maxlen=14
     ```


## Configuration

| property   |                          Description                 | Default |
| ---------- |------------------------------------------------------| ------- |
| minlen     |   Minimum length of the password                     | 6 |
| maxlen     |   Maximum length of the password                     | 16 |
| minuchars  |   Minimum upper case characters required in password | 1 |
| minlchars  |   Minimum lower case characters required in password | 1 |
| minnumbers |   Minimum numbers required in password               | 1 |
| minschars  |   Minimum special characters in the password         | 1 |


### Features
 * Generate a simple password of default length 6-16.
 * Generate a password with custom properties.
 * Generate a password from given characters.
 * Generate Non Duplicate Password.
 * Available at https://random-pg.herokuapp.com/


## Contributions
Contributions are welcomed via PR.

Frontend by: [Arthur Coelho](https://github.com/ArthurCueio)
Contributions from previous repo:
  * [Amar Prabhu](https://github.com/amar-prabhu-29)

## License
 * [MIT](LICENSE)
