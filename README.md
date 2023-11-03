class Employee:
    def _init_(self, emp_id, emp_name, emp_salary):
        self.emp_id = emp_id
        self.emp_name = emp_name
        self.emp_salary = emp_salary

    def get_employee_details(self):
        return f"Employee ID: {self.emp_id}, Employee Name: {self.emp_name}, Employee Salary: {self.emp_salary}"

employee1 = Employee(101, "John Doe", 50000)
print(employee1.emp_id)
print(employee1.emp_name)  
print(employee1.emp_salary)  

print(employee1.get_employee_details())
