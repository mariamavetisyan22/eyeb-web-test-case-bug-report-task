# eyeball web test cases and bug reports 

The task of Geex-Arts, includes test cases and Bug Reports of Sign In/Sign Up pages.

- This is the test documentation of the task [Geex-Arts](https://eyeb-web-git-dev-eyeb.vercel.app/feed) which includes a test document file of the Sign Up/Log In pages, you can find the test cases and bug reports, also test environment parameters, requirements, and possible test scenarios, test data (in one table for easy use).

  There are the scenarios of the documented file.
- The Test Cases.doc file indicates test cases for the following scenarios.
  
  1. Check Sign Up using a valid/invalid email.
  2. Check Sign Up using a valid/invalid phone.
  3. Check Sign In using a valid/invalid existing phone.
  4. Check Sign In using a valid/invalid existing email.
  5. Check Sign In using a valid existing username.
  6. Check Forgot Password on the Sign In page.

## **Test Objective**
 
Testing the page [Geex-Arts](https://eyeb-web-git-dev-eyeb.vercel.app/feed) aims to ensure that all the essential functionalities and features work as intended and provide a seamless user experience during the sign-up and login process.

## **Test Environment**
Parameters | Values | 
--- | --- |
Operating System | Windows 11 Home, 22H2, 22621.1928 |
Browser | Chrome: 114.0.5735.199 (Official Build) (64-bit) |
Screen Resolution | 1920x1080 pixels |

## **Requirements**

- **Password:** field must be filled with English alphabet letters and include three character types: lowercase letters, uppercase letters and numbers. You also have the option to use any of these special characters: # [ ] ( ) @ $ & * ! ? | , . ^ / \ + _ -
   - 8 — 10 characters
   - At least one uppercase letter (ABC...)
   - At least one lowercase letter (abc...)
   - At least one number (123...)


## **Test Data**
#### _Valid Test Data_
  - **email:** m@mailinator.com; test#gmail.com; test; mar.test.avetis@gmail.com
  - **Password:** Testuser1!; test; 123; !"£$; TEST; 

## **Test Execution Results**
Parameters | Values | 
--- | --- |
**Total** | **$${\color{light-gray}23}$$** |
Passed | $${\color{green}23}$$ |
Failed | $${\color{red}5}$$ |