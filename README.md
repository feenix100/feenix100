# About Me

I’m currently a student pursuing a degree in Networking and Systems Administration. My goal is to transition from my current role in a warehouse simulation to a more fulfilling job in the tech industry. Currently, my job doesn’t allow me to afford luxuries like a Tesla, but I’m motivated to change that.

### Interests
- 👀 **Languages & Technologies**: Python, JavaScript
- 💞️ **Collaboration Goals**: Exploring connections between the human brain and digital computational devices

### How to Reach Me
- 📫 Find my neural link address... 

Feel free to connect if you share similar interests or if you're working on groundbreaking projects!
  
```javascript
function calculateBillsAndPaycheck() {
    // Prompt the user for the paycheck amount
    let paycheck = prompt("Enter the paycheck amount: $");
    
    // Ensure the input is a valid number
    paycheck = parseFloat(paycheck);
    
    if (isNaN(paycheck)) {
        console.log("Invalid input. Please enter a numeric value for the paycheck amount.");
        return;
    }
    
    // Calculate the monthly bills as $100 more than each paycheck to simulate the actual debt accumlated in this simulated life
    let monthlyBills = paycheck + 100;
    
    // Display the slowly increasing snowball of debt
    console.log(`Paycheck: $${paycheck.toFixed(2)}`);
    console.log(`Bill Payment: $${monthlyBills.toFixed(2)}`);
    console.log(`Debt accumulated every paycheck: $${(monthlyBills - paycheck).toFixed(2)}`);
}

// Call the function to see how my life is going into debt
calculateBillsAndPaycheck();

```
