# Codeigniter Password Hash Library

Is a Codeigniter 3 library

Implemented from **"Salted Password Hashing"** (https://crackstation.net/hashing-security.htm)

Forked from https://github.com/defuse/password-hashing

### Instalation
- Put the `Cipasswordhash.php` to your `application/libraries/` directory
- then you can load it from your controller or model with
```php
    $this -> load -> library('cipasswordhash');
```
### Usage
- Create hashed string via
 
 ```php
    $this -> cipasswordhash -> create_hash($password);
 ```
 
- Verify the hashed string via
 
 ```php
    $this -> cipasswordhash -> validate_password($password,$right_password);
 ```
 
### To do
- Create login example
 

#### Credit 
- https://github.com/defuse/password-hashing
