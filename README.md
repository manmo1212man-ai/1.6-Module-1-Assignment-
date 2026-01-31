// --- GLOBAL VARIABLE ---
// Requirement: Created at the top level, accessible everywhere.
let appStatus = "Running";

// --- OBJECT VARIABLE ---
// Requirement: Create an object using const and assign values.
const projectData = {
    title: "Intro to JS Assignment",
    version: 1.0,
    isComplete: true
};

function processData() {
    // --- BLOCK VARIABLE ---
    // Requirement: Created inside a block (this function), identified with comments.
    let baseValue = 100;

    // --- MATHEMATICAL OPERATIONS ---
    // Requirement: Perform math on variables.
    let multiplier = 5;
    let totalScore = (baseValue * multiplier) + 25;

    // --- STRING VARIABLE ---
    // Requirement: Create, comment, and log a string.
    // This string variable stores the final result message for the user.
    let resultMessage = "The final calculated value is: ";

    // --- OUTPUT TO CONSOLE ---
    // Requirement: Write variable values to the console.
    console.log(resultMessage);
    console.log(totalScore);
    console.log("Current App Status:", appStatus);
    console.log("Project Object Info:", projectData);
}

// Execute the function
processData();
