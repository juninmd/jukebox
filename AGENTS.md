```markdown
# AGENTS.md - AI Coding Agent Guidelines

These guidelines are designed to ensure consistent, maintainable, and high-quality AI coding agent development within the AGENTS repository. Adherence to these principles is crucial for maximizing productivity and minimizing maintenance overhead.

## 1. DRY (Don't Repeat Yourself)

*   All functions, classes, and modules should have single, well-defined responsibilities.
*   Avoid duplication of logic across multiple files.
*   Leverage existing code where possible and refactor accordingly.
*   Document all reusable components clearly.

## 2. KISS (Keep It Simple, Stupid)

*   Code should be easy to understand and maintain.
*   Favor concise, readable code over overly complex solutions.
*   Minimize cognitive load for developers.
*   Keep algorithms and data structures to a minimum.

## 3. SOLID Principles

*   **Single Responsibility Principle:** Each class/module should have one, and only one, reason to change.
*   **Open/Closed Principle:** The system should be extensible without modification.  New features should be added via new classes/modules, not by modifying existing ones.
*   **Liskov Substitution Principle:**  Subclasses must be substitutable for their base classes without altering the correctness of the program.
*   **Interface Segregation Principle:** Clients should not be forced to depend on methods they do not use.
*   **Dependency Inversion Principle:** High-level modules (e.g., classes) should not depend on low-level modules (e.g., classes).  Interfaces define the contract, and implementations implement it.

## 4. YAGNI (You Aren't Gonna Need It)

*   Only implement functionality that is explicitly required.
*   Avoid unnecessary complexity or features.
*   Refactor to remove features that are no longer needed.
*   Prioritize core functionality and essential features.

## 5. Code Structure & Best Practices

*   **Modularization:** Break down the codebase into small, logical modules.  Each module should have a single, well-defined purpose.
*   **Naming Conventions:** Use consistent and descriptive naming conventions.  (See examples in the documentation)
*   **Comments:** Provide clear and concise comments to explain complex logic or non-obvious code.  Focus on *why* not *what*.
*   **Error Handling:** Implement robust error handling to prevent unexpected crashes and provide informative error messages.
*   **Logging:**  Implement logging to track program execution and errors.
*   **Data Structures:** Choose appropriate data structures for each task.
*   **Code Style:** Follow a consistent code style (e.g., PEP 8 for Python).

## 6. File Length & Test Coverage

*   **Maximum Code Length:** Each file should be strictly limited to 180 lines of code.
*   **Test Coverage:**  Achieve a minimum of 80% test coverage for all functions and classes.  Coverage should be verified through automated test frameworks.
*   **Unit Tests:** Prioritize writing comprehensive unit tests for each function/class.  Focus on edge cases and boundary conditions.

## 7.  Development Process

*   **Version Control:** Use Git for version control and commit frequently.
*   **Code Reviews:**  Conduct regular code reviews to ensure code quality and adherence to best practices.
*   **Documentation:**  Maintain clear and up-to-date documentation.

## 8.  Specific Considerations for AGENTS (AI Agent Development)

*   **Agent Lifecycle Management:**  Provide clear documentation on how agents are designed to be deployed and managed.
*   **State Management:**  Implement a robust state management system for agents.
*   **Interaction Modeling:**  Clearly define the agent's interaction model and its capabilities.
*   **API Design:**  Establish well-defined APIs for agent communication and data exchange.

## 9.  Testing Frameworks & Tools

*   Use a testing framework (e.g., pytest, unittest) as per the existing framework.
*   Implement automated tests for core functionality.

## 10.  Documentation (within code)

*   **Docstrings:**  Use docstrings to explain the purpose, parameters, and return values of functions and classes.
*   **Inline Comments:** Use inline comments to clarify complex logic.

These guidelines are intended as a framework.  The team responsible for maintaining the AGENTS repository will have the final say in interpreting and enforcing these rules.
```