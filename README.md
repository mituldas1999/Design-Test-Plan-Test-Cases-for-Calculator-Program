# Calculator Program Test Report

## Test Case Summary

- **Product Name:** Calculator Program
- **Module Name:** Contact
- **Epic:** SH-091
- **Developer Name (TL):** Mitul Das
- **Test Case Developed By:** Mitul Das
- **Test Case Reviewed By:** Genesys Softwares
- **TC Start Date:** 24/02/2024
- **TC End Date:** 24/02/2024
- **TC Execution Start Date:** --
- **TC Execution End Date:** --

### Overall Test Results

- **Total Test Cases:** 20
- **Pass:** 10 ✅
- **Fail:** 10 ❌
- **Warning:** 0 ⚠️

## Detailed Test Cases

| Test Case ID/Name | Test Case Description                                        | Precondition                                               | Test Data                                              | Step Description                                              | Expected Result                                          | Actual Result                                  | Status | Remarks                                       |
| ------------------ | ------------------------------------------------------------ | ---------------------------------------------------------- | ------------------------------------------------------- | ------------------------------------------------------------ | -------------------------------------------------------- | ---------------------------------------------- | ------ | ---------------------------------------------- |
| TC01               | Test subtraction where the result is a negative number.     |                                                              | "1. Enter the number 5.<br>2. Press the "-" key.<br>3. Enter the number 9.<br>4. Press the "=" key." | Verify the calculator can perform subtraction that results in a negative number and display it accurately. | The calculator displays -4.                             | The calculator displays -4.                     | PASS   |                                                |
| TC02               | Test multiplying a positive number by a negative number.     |                                                              | "1. Enter the number 6.<br>2. Press the "*" key.<br>3. Enter the number -3.<br>4. Press the "=" key." | Check if the calculator can multiply a positive number by a negative number and show the correct product. | The calculator displays -18.                           | The calculator displays -18.                    | PASS   |                                                |
| ... (Truncated for brevity)                                 |                                                              |                                                          |                                                        |                                                              |                                                        |                                              |        |                                                |
| TC20               | Test the calculator's handling of numbers raised to extremely large | Calculator app is open and supports exponentiation.       | "1. Enter the number 9.<br>2. Press the exponentiation key.<br>3. Enter a very large exponent<br>4. Press the "=" key." | Check the calculator's handling of extremely large exponents, ensuring it does not crash or freeze and handles the input gracefully. | The calculator either displays an overflow error or manages the large exponent gracefully. | The calculator crashed and had to be restarted. | FAIL   | If the calculator crashes or freezes                  |

*Note: The detailed test case table is truncated for brevity.*

## Conclusion

The Calculator Program test resulted in a mixed outcome, with 10 test cases passing, 10 failing, and no warnings. Failures are mainly related to handling specific scenarios like division by zero, exceeding maximum capacity, handling invalid syntax, and responsiveness after rapid input. Recommendations for improvements and fixes are suggested in the "Remarks" column for each failing test case.
