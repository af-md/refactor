# basic coding standards - examples in simple javascript


# variable naming

## clear readability

    // Bad Variable Names
    let a = 10;
    let b = "John";
    let c = true;

    //Good Variable Names
    let numberOfStudents = 25;
    let customerName = "John Doe";
    let isLoggedIn = true;
 
 ## readible, clear, but also precise
    
    var xCoord1 = 5;
    var yCoord1 = 10;

    var xCoordinate = 5;
    var yCoordinate = 10;

    var numStudents = 25;
    var studentsArray = ['John', 'Jane', 'Mike'];

    var studentCount = 25;
    var studentNames = ['John', 'Jane', 'Mike'];


    var userInputStr = 'Hello';
    var userInputNum = 42;

    var userInputString = 'Hello';
    var userInputNumber = 42;

## now do some yourself

    // Bad Example
    let a = 100; // Player's health points
    let b = 50; // Player's maximum health points
    let c = 20; // Player's current health level

    // Bad Example
    let x = 0; // Current player score
    let y = 100; // Maximum achievable score
    let z = 10; // Number of points earned in the current level

    // Bad Example
    let p = true; // Setting indicating if sound is enabled
    let q = 3; // Difficulty level (1 - Easy, 2 - Medium, 3 - Hard)
    let r = 60; // Time limit in seconds


## function naming

    function functionToCalculateTheSquareRootOfAGivenNumberAndReturnTheResult(number) {
        // Function logic to calculate the square root of the number
    }


    function aFunctionThatReadsAFileAndReturnsAnArrayOfLinesFromTheFileBasedOnTheProvidedFilePath(filePath) {
        // Function logic to read a file and return an array of lines from the file
    }


    function getPrimeNumbers(limit) {
        // Function logic to generate an array of prime numbers up to the given limit
    }
    
 ## function parameters
 
     function calculateArea(b, h) {
      // Bad Example
      let result = 0.5 * b * h;
      return result;
    }

    function calculateArea(base, height) {
      // Good Example
      let area = 0.5 * base * height;
      return area;
    }

    function greet(n) {
      // Bad Example
      return "Hello, " + n + "!";
    }

    function greet(name) {
      // Good Example
      return "Hello, " + name + "!";
    }

    function calculateSum(n1, n2, n3) {
      // Bad Example
      let sum = n1 + n2 + n3;
      return sum;
    }

    function calculateSum(number1, number2, number3) {
      // Good Example
      let sum = number1 + number2 + number3;
      return sum;
    }


## if statements

    function getLetterGrade(grade) {
      if (grade >= 90) {
        return 'A';
      } else if (grade >= 80) {
        return 'B';
      } else if (grade >= 70) {
        return 'C';
      } else if (grade >= 60) {
        return 'D';
      } else {
        return 'F';
      }
    }

    function getLetterGrade(grade) {
      switch (true) {
        case grade >= 90:
          return 'A';
        case grade >= 80:
          return 'B';
        case grade >= 70:
          return 'C';
        case grade >= 60:
          return 'D';
        default:
          return 'F';
      }
    }
    
     function getDayOfWeek(dayNumber) {
      if (dayNumber === 1) {
        return 'Sunday';
      } else if (dayNumber === 2) {
        return 'Monday';
      } else if (dayNumber === 3) {
        return 'Tuesday';
      } else if (dayNumber === 4) {
        return 'Wednesday';
      } else if (dayNumber === 5) {
        return 'Thursday';
      } else if (dayNumber === 6) {
        return 'Friday';
      } else if (dayNumber === 7) {
        return 'Saturday';
      } else {
        return 'Invalid day';
      }
    }
    
    
     function getDayOfWeek(dayNumber) {
      switch (dayNumber) {
        case 1:
          return 'Sunday';
        case 2:
          return 'Monday';
        case 3:
          return 'Tuesday';
        case 4:
          return 'Wednesday';
        case 5:
          return 'Thursday';
        case 6:
          return 'Friday';
        case 7:
          return 'Saturday';
        default:
          return 'Invalid day';
      }
    }



    
