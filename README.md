# alt_mongodb_assignment
 MongoDB Operators and Projection on Employee Data


- Complete all 4 questions using Python and PyMongo.
- Include proper error handling and comments in your code.
- Test your solutions with the provided sample data.
- **Use the `faker` library to generate 10,000 sample employee documents 


## Tasks

Write Python functions using PyMongo to solve the following:

1. **High Performers Query:** Find all employees with performance rating >= 4.0 **AND** salary > 80,000. Return only their name, department, salary, and performance rating.
2. **Experience-Based Filtering:** Find employees with 5-10 years of experience (inclusive) who earn between $70,000 and $120,000. Project only essential contact information (name, email, department).
3. **Salary Range Analysis:** Find employees whose salary is **NOT** in the range of $60,000-$100,000. Show their full name (concatenated), current salary, and years of experience.
4. **Recent Hires:** Find employees hired in the last 2 years with performance rating > 3.5. Return custom fields showing "full_name", "tenure_months", and "annual_salary".
