#### Experiment 8 — Temperature Conversion (Celsius ↔ Fahrenheit)



#### **Aim**



**To develop an Android application that converts temperature values between Celsius and Fahrenheit using input from an EditText and displays the result via buttons and a TextView.**



#### **Algorithm**



1. **Create a new Android project and design activity\_main.xml with:**



* **An EditText for temperature input (numeric decimal type).**
* **A "Convert to Fahrenheit" button.**
* **A "Convert to Celsius" button.**
* **A "Clear" button.**
* **A TextView to display the result.**





**2. In MainActivity.java, declare and initialize variables for all UI components in onCreate().**

**3. Set an OnClickListener on the Convert to Fahrenheit button:**



* **Read the value from the EditText.**
* **If not empty, parse it as a double (Celsius value c).**
* **Apply the formula: F = (c × 9/5) + 32**
* **Display the result in the TextView.**
* **If empty, prompt the user to enter a value.**





**4. Set an OnClickListener on the Convert to Celsius button:**



* **Read the value from the EditText.**
* **If not empty, parse it as a double (Fahrenheit value f).**
* **Apply the formula: C = (f − 32) × 5/9**
* **Display the result in the TextView.**
* **If empty, prompt the user to enter a value.**



**5. Set an OnClickListener on the Clear button:**



* **Clear the EditText and reset the TextView to a default message.**



**6. Run the application, enter temperature values, and verify both conversions produce correct results.**

