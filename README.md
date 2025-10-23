LECTURER'S NAME:MR Z.KALUBA
STUDENT NAME:OWEN MUKELA MUTUMBA
ID:202400975
COURSE CODE:251
COURSE NAME:WEB TECHNOLOGIES 

## Project Description
This is a *Single-File Web App* that allows users to:  
1. *Solve quadratic equations* of the form ax² + bx + c = 0.  
2. *Calculate a grade* from a numeric score (0–100) based on a predefined grade scale.  

The app validates user inputs, provides clear error messages, and shows results in a neatly formatted way.  

---

## How to Run
1. Download or clone the repository.  
2. Open the file index.html in any modern web browser (Chrome, Edge, Firefox, etc.).  
3. Use the two sections on the page:  
   - *Quadratic Solver*: Enter values for a, b, and c, then click *Compute*.  
   - *Grade Calculator: Enter a score (0–100), then click **Compute*.  
4. Use the *Reset* buttons to clear inputs and results.  

No internet connection or server is required – the app runs fully offline.

---


- *Quadratic Solver*
  - Calculates discriminant D = b² - 4ac.  
  - Determines the nature of roots:
    - Two distinct real roots (D > 0)  
    - One repeated real root (D = 0)  
    - Two complex conjugate roots (D < 0)  
  - Displays roots with up to 2 decimal places.  
  - Shows clear error messages for invalid input or a = 0.

- *Grade Calculator*
  - Converts numeric scores to letter grades using the following scale:
    - 85–100 → A+  
    - 75–84 → A  
    - 65–74 → B+  
    - 60–64 → B  
    - 55–59 → C+  
    - 50–54 → C  
    - 0–49 → D  
  - Handles edge cases correctly (0, 49, 50, 55, 60, 65, 75, 85, 100).  
  - Validates input to ensure numbers are in range [0–100].

---

## Test Cases

### Quadratic Solver
| a  | b  | c  | Expected Result                          |
|----|----|----|-----------------------------------------|
| 1  | -3 | 2  | x₁ = 2, x₂ = 1 (Two distinct real roots) |
| 1  | 2  | 1  | x = -1 (One repeated real root)        |
| 1  | 2  | 5  | x₁ = -1 + 2i, x₂ = -1 - 2i (Complex)  |
| 0  | 2  | 1  | Error: a cannot be 0                    |

### Grade Calculator
| Score | Expected Grade |
|-------|----------------|
| 100   | A+             |
| 85    | A+             |
| 82    | A              |
| 75    | A              |
| 70    | B+             |
| 65    | B+             |
| 60    | B              |
| 55    | C+             |
| 50    | C              |
| 49    | D              |
| 0     | D              |


## GitHub Commits Suggestion
1. *Initial commit*: Add index.html structure.  
2. *Quadratic Solver*: Implement solver logic with validation.  
3. *Grade Calculator*: Implement grading system with validation.  
4. *Styling & Testing*: Add CSS for layout and complete final testing.


