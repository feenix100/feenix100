# About Me

I’m currently a student pursuing an undergraduate degree in Computer Science. My goal is to escape from the warehouse simulation loop I am stuck in. Then find a more fulfilling job in the tech industry simulation. 

### Interests
- 👀 **Languages & Technologies**: Python, JavaScript, Java
- 💞️ **Collaboration Goals**: Exploring connections between the human brain and digital computational devices. I want to develop code for brain embedded devices. How can we connect computers to the human brain?
- Your eyeballs could become cameras, imagine taking a picture of your point of view, literally, then sharing that with other people, the same way that your eyes viewed it. We just need the right hardware installed, we can use javascript for everything else...

### How to Reach Me
- 📫 Read my thoughts and find my neural link address... 

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
