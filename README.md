I am currently a student, working towards a degree in networking and systems administration.
I am trying to break out of this warehouse simulation I am stuck in and get a better job in the tech industry. I could never afford to buy a tesla at my current job.


- 👀 I’m interested in python, javascript, artificial intelligence

- 💞️ I’m looking to collaborate on connecting the human brain to digital computational devices.

- 📫 How to reach me: find my neural link address...
  
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
