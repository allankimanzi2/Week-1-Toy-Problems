// Challenge 1: Student Grade Generator

function calculateGrade() {
  const userInput = prompt("Enter student marks (0-100):");
  const marks = parseFloat(userInput);

  if (isNaN(marks) || marks < 0 || marks > 100) {
    console.log("Invalid input. Marks should be between 0 and 100.");
    return;
  }

  if (marks > 79) {
    console.log("Grade: A");
  } else if (marks >= 60) {
    console.log("Grade: B");
  } else if (marks >= 50) {
    console.log("Grade: C");
  } else if (marks >= 40) {
    console.log("Grade: D");
  } else {
    console.log("Grade: E");
  }
}

calculateGrade();
