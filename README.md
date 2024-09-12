# 2.5-Taxes 

#### Objective:
Create a Python program that calculates the income tax for a user based on their annual income, applies tax exemptions, and categorizes them into different tax brackets. Additionally, apply a special exemption if the number of dependents is even.

#### Instructions:
1. **Prompt the user** to enter their annual income.
2. **Prompt the user** to enter the number of dependents.
3. **Calculate the tax** based on the following tax brackets:
   - Income up to $10,000: 0% tax
   - Income from $10,001 to $30,000: 10% tax
   - Income from $30,001 to $50,000: 20% tax
   - Income above $50,000: 30% tax
4. **Apply a tax exemption** of $2,000 per dependent.
5. **Apply an additional special exemption** of $500 if the number of dependents is even.
6. **Use `if`, `elif`, and `else` statements** along with logical operators to determine the tax amount.
7. **Use the modulus operator** to check if the number of dependents is even or odd and apply the special exemption.
8. **Display the tax amount, the corresponding tax bracket, and the even/odd status** of the number of dependents to the user.

#### Example:
Input:
```
Enter your annual income: 45000
Enter the number of dependents: 2
```
Output:
```
Your tax amount is: $4500.00
You are in the 20% tax bracket.
You have an even number of dependents.
```

