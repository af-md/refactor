# basic coding standards


## variable naming



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



    
