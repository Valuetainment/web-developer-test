# Interview Instructions

## Objective

Enhance the application by adding features related to the "Expected Rate of Return" and "Projected Balance."

## Tasks

1. **Add Input Field for Expected Rate of Return**

   - **Description**: Introduce a new input field labeled "Expected Rate of Return" where users can input a numerical value.
   - **Requirements**:
     - The input should accept percentage values (e.g., 7 for 7%).
     - Ensure the input field is clearly labeled and positioned appropriately within the user interface.

2. **Add Projected Balance Column to Leaderboard Table**

   - **Description**: Create a new column in the Leaderboard table titled "Projected Balance."
   - **Calculation**:
     - The "Projected Balance" should be calculated by adding the product of the current balance and the expected rate of return to the current balance.
     - **Example**:
       - If the Balance is $100,000 and the Expected Rate of Return is 7%, the Projected Balance should be $107,000.
   - **Requirements**:
     - Ensure the column is formatted to display currency values.
     - The column should update dynamically as the expected rate of return is modified.

3. **Add Projected Balance Line to Chart**
   - **Description**: Incorporate a new line in the existing chart to represent the "Projected Balance" values.
   - **Requirements**:
     - The line should be visually distinct from other data lines in the chart.
     - Ensure the chart updates in real-time as the expected rate of return or balance changes.

## Notes

- Ensure all new features are tested for accuracy and usability.
- Maintain consistency with the existing design and functionality of the application.
