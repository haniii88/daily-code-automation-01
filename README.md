/* Daily Update Script — 01 */
/* This script generates a random fact every time it runs */

function generateDailyFact() {
    const facts = [
        "The sky contains billions of tiny particles scattering sunlight.",
        "JavaScript was created in just 10 days.",
        "Honey never spoils and can last thousands of years.",
        "Octopuses have three hearts.",
        "A day on Venus is longer than its year."
    ];
    
    const fact = facts[Math.floor(Math.random() * facts.length)];
    console.log("Daily Fact:", fact);
}

generateDailyFact();
