# Hishabee Business App Manual Testing

## Project Overview
This repository contains the test case report for the **Hishabee Business App**, focusing on the **Inventory Management** and **Sales Management** modules. The objective of this testing is to ensure the functionality, usability, and reliability of the application.

---

## Contents

1. **Hishabee Business App Manual Testing.xlsx**  
   Contains detailed test cases, execution results, and bug tracking across four organized sheets:
   - **Test Summary**: An overview of the testing process, including key metrics like total test cases, pass/fail counts, and execution progress.  
   - **Inventory Management**: A structured list of test cases for **Inventory Management** module with detailed steps, expected outcomes, and actual results. 
   - **Sales Management**: A structured list of test cases for **Sales Management** module with detailed steps, expected outcomes, and actual results.
   - **Bug Report**: A detailed log of issues found during testing, including screenshots, priority & severity levels, and status.  
   - **Mindmap**: A representation of test coverage and strategy in a clear, hierarchical structure.

2. **Mindmap.png**  
   A visual representation of the testing approach and strategy derived from the mindmap sheet.
   
   ![Mindmap](./Mindmap.png)

---

### Description of Excel Sheets  

1. **Test Summary**  
   - Provides an at-a-glance overview of the testing effort.  
   - Includes key metrics like the total number of test cases, pass/fail breakdown, charts, and overall execution status.  

2. **Inventory Management**  
   - Contains detailed test cases for Inventory Management Module structured with:   
     - Test Case ID  
     - Test Case Description
     - Pre Conditions
     - Priority
     - Section
     - Steps
     - Test Data  
     - Expected vs. Actual Results
     - Status (Pass, Fail, Not Implemented)
     - Bug Screenshots  
     - Comments

3. **Sales Management**  
   - Contains detailed test cases for Sales Management Module structured with:  
     - Test Case ID  
     - Test Case Description
     - Pre Conditions
     - Priority
     - Section
     - Steps
     - Test Data  
     - Expected vs. Actual Results
     - Status (Pass, Fail, Not Implemented)
     - Bug Screenshots  
     - Comments

4. **Mindmap**  
   - Highlights test strategy and coverage in a visual format for better understanding.  
   - Acts as a guide for which areas were tested.  

5. **Bug Report**  
   - Logs all identified bugs with detailed information, including:  
     - Bug ID  
     - Description    
     - Steps to Reproduce
     - Environment
     - Module
     - Section
     - Test Case ID
     - Priority and Severity
     - Bug Screenshot links (used JIRA tool)  
     - Responsible QA

---

## Types of Testing Performed

1. **Functionality Testing**: Validates the application against the specified requirements.
2. **Usability Testing**: Assesses user-friendliness of the application.
3. **Negative Testing**: Tests application behavior with invalid inputs.
4. **Reliability Testing**: Evaluates the application's ability to perform under defined conditions.

---

## Test Case Summary

- **Total Test Cases**: 65
- **Passed**: 57
- **Failed**: 6
- **Not Implemented**: 2
- **Pass Rate**: 87.69%

---

## Test Cases and Results

### Inventory Management Module
- **Total Test Cases**: 25  
- **Passed**: 22  
- **Failed**: 2  
- **Not Implemented**: 1  
- **Pass Rate**: 88.00%

#### Relevant Sections:
1. **Product List**
	- Test's Include:
     - Adding a new product with required details (e.g., name, price, quantity).
     - Editing or deleting existing products.
     - Validating product details (e.g., unique product names)
	   and more.

2. **Stock Book**
	- Test's Include:
     - Adjusting stock levels after sales or purchases.
     - Checking low-stock alerts when stock falls below a threshold.
     - Validating consistency between the "Stock Book" and "Product List."
	   and more.

3. **Stock Count (on Dashboard)**
	- Test's Include:
     - Accurate calculation of total stock count after inventory changes.
     - Handling edge cases like adding or deleting multiple products simultaneously.
	   and more.
	
### Sales Management Module
- **Total Test Cases**: 40  
- **Passed**: 35  
- **Failed**: 4  
- **Not Implemented**: 1  
- **Pass Rate**: 87.50%

#### Relevant Sections:
1. **Sales Book**
	- Test's Include:
     - Adding new sales entries.
     - Viewing, editing, or deleting sales entries.
     - Handling payments for due sales.
 	   and more.

2. **Due Book**
	- Test's Include:
     - Recording and updating due payments.
     - Sending payment reminders.
     - Updating due status upon payment.
	   and more.

3. **Today’s Sale/This Month's Sale (on Dashboard)**
	- Test's Include:
     - Accurate calculation of daily and monthly sales amounts.
     - Proper updates when sales are added or edited.
     - Handling scenarios with no recorded sales.
	   and more.

---

## Tools Used

1. **JIRA (for Bug Tracking)**  
   - **Purpose**: To track bugs and manage project tasks. Bug screenshots are linked using JIRA.  
   - **Website**: [JIRA](https://www.atlassian.com/software/jira)

2. **Xmind (for Mindmaps)**  
   - **Purpose**: To create a detailed test strategy and coverage mind map.  
   - **Download**: [Xmind](https://xmind.app/download/)

---

## Test Execution Timeline

- **Test Case Writing Start Date**: 10/12/2024
- **Test Execution Start Date**: 10/12/2024
- **Test Case Writing End Date**: 12/12/2024
- **Test Execution End Date**: 12/12/2024

---

## How to Use  

### Clone the Repository  

```bash  
git clone https://github.com/AbirBony21/Hishabee-Business-App-Manual-Testing.git 
cd Hishabee-Business-App-Manual-Testing 
```
## OR

### Download the ZIP

## Getting Started

To run the test cases, ensure the Hishabee Business App is installed. Follow the testing steps outlined in the **Hishabee Business App Manual Testing.xlsx** file for comprehensive guidance.

# HAPPY TESTING !!! :tada:

