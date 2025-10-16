======================
Form Design Guidelines
======================

Conventions
-----------
To enable rapid application development, the Backend follows some standard conventions.

- Engagement Form is always named in singular. If you want to store a list of households in the database, you should name the Engagement Form as **Household**
- The name of the Engagement Form cannot be more than 61 characters
- The labels are always named such that the first letter of each word is in upper case and all other letters are in lower case, e.g **First Name**
- When assigning field names, use **Snake Case** naming convention. Snake case separates each word with an underscore character (_). When using snake case, all letters need to be lowercase e.g **first_name**. Snake case is used for creating variable and field names.


Form Responsibility
-------------------

An engagement form should have only a single purpose. This is called the Single Responsibility Principle (SRP)

A "single" in form design refers to the Single Responsibility Principle (SRP), which states that a form should have only one reason to change. This means each tool should have a single, focused responsibility or job to do. Adhering to this principle leads to more understandable, maintainable, and flexible tools. 


.. note::

    - **One job, one reason to change**: The core idea is that if a tool has multiple responsibilities, such as receiving input from clients and also working on the input, it has multiple reasons to change. By separating these into different tools (e.g., one for validation, one for handling approval process), each tool now has only one responsibility and one reason to change.
