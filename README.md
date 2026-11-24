# Tholkapian_N_Data_science_with_python_exp01
# Employee Payroll Calculation
name = input("Enter Employee Name: ")
emp_id = input("Enter Employee ID: ")
basic = float(input("Enter Basic Pay: "))

hra = 0.15 * basic
da = 0.10 * basic
gross = basic + hra + da
tax = 0.08 * gross
net = gross - tax

print("\n--- Employee Salary Report ---")
print(f"Employee Name: {name}")
print(f"Employee ID: {emp_id}")
print(f"Basic Pay: {basic}")
print(f"HRA: {hra}")
print(f"DA: {da}")
print(f"Gross Salary: {gross}")
print(f"Tax Deducted: {tax}")
print(f"Net Salary: {net}")
