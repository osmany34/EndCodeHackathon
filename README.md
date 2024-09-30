# StudentManager Project

This project aims to create a student management system that operates on the ICP Testnet. The project includes smart contract functions for managing students' points and storing student information.

## Project Functions

- **addStudent**: Adds a new student.
- **addPoints**: Increases the points of an existing student.
- **subtractPoints**: Decreases the points of an existing student.
- **getStudentInfo**: Retrieves information about a specific student.

## Technologies Used

- **Motoko**: The smart contract language.
- **ICP Testnet**: Runs on the Internet Computer platform.

## How to Run the Project

### Steps:

1. Go to Motoko Playground (https://m7sm4-2iaaa-aaaab-qabra-cai.raw.ic0.app/).
2. Create a new project in the Motoko Playground and paste the above code.
3. Test the functions like `addStudent`, `addPoints`, `subtractPoints`.
4. Save the changes and deploy the contract.

### Example Tests:

```bash
# Test adding a student
addStudent("Ali");

# Test adding points
addPoints("Ali", 10);

# Test subtracting points
subtractPoints("Ali", 5);

# Test retrieving student information
getStudentInfo("Ali");
