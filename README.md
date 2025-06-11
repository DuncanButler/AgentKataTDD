# AgentKataTDD: String Calculator Kata with Ping Pong Programming

Welcome to the AgentKataTDD repository! This project is a C# implementation of the classic String Calculator Kata, designed to be completed using the **Ping Pong Programming** technique. This approach alternates between a human programmer and GitHub Copilot (AI) to incrementally build the solution using Test-Driven Development (TDD).

## Repository Structure

- `CalculatorKata/`
  - `src/StringCalculator.cs` — The main implementation of the String Calculator.
  - `Tests/Calculator.Tests.cs` — NUnit test suite for the String Calculator.
  - `Specs/StringCalculatorSpec.md` — The evolving specification file, updated as requirements are completed.
- `README.md` — This file.
- `.github/copilot-instructions.md` — Detailed rules for Ping Pong Programming.

## How to Use This Repository

### Prerequisites
- [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0) or later installed on your system.
- A terminal or command prompt (PowerShell, CMD, or Bash).

### Getting Started
1. **Clone the repository:**
   ```sh
   git clone <your-repo-url>
   cd AgentKataTDD
   ```
2. **Restore dependencies:**
   ```sh
   dotnet restore CalculatorKata/CalculatorKata.csproj
   ```

### The Ping Pong Programming Process

Ping Pong Programming is a collaborative TDD workflow where two participants (a human and an AI) alternate roles:

1. **The Programmer:**
   - Writes a failing test for the next requirement.
   - Commits the change.
2. **The AI (Copilot):**
   - Makes the test pass in the simplest way possible.
   - Refactors the code if needed.
   - Updates the specification file (`Specs/StringCalculatorSpec.md`) to mark the requirement as complete.
   - Writes the next failing test for the programmer.
   - Commits the changes.
3. **Repeat:**
   - Alternate roles and repeat steps 1–2 until all requirements are complete.

#### Rules
- Only one failing test should be added at a time.
- Each participant only does their assigned steps before handing off.
- Refactoring is done after making a test pass, before writing the next test.
- The specification file is updated after a test passes to reflect the current state of the feature.
- See `.github/copilot-instructions.md` for full details.

### How to Run the Tests

You can run the tests at any time to verify your progress. The project uses [NUnit](https://nunit.org/) for testing.

#### From the Command Line (PowerShell, CMD, or Bash):

1. **Navigate to the project directory:**
   ```sh
   cd CalculatorKata
   ```
2. **Run the tests:**
   ```sh
   dotnet test
   ```
   This will build the project (if needed) and execute all tests in the `Tests` folder. The results will be displayed in the terminal.

#### Example Output
```
Test run for ...\CalculatorKata\bin\Debug\net9.0\CalculatorKataTests.dll (.NETCoreApp,Version=v9.0)
Starting test execution, please wait...
Passed!  - Failed: 0, Passed: 5, Skipped: 0, Total: 5, Duration: 50 ms
```

### How to Add a New Requirement
- Add a new unchecked item to `Specs/StringCalculatorSpec.md` if you want to extend the kata.
- Follow the Ping Pong Programming process for each new requirement.

## Additional Notes
- Keep your code and tests clean and well-named.
- Use `var` for local variables when the type is obvious.
- Use PascalCase for class and method names, camelCase for parameters and local variables.
- For more details, see the `.github/copilot-instructions.md` file.

---

Happy coding and have fun with Ping Pong Programming!
