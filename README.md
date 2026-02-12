# Simple Interest Formula: SI = (P * T * R) / 100
def calculate_simple_interest(p, t, r):
    return (p * t * r) / 100

principal = float(input("Enter the principal amount: "))
time = float(input("Enter the time period (in years): "))
rate = float(input("Enter the rate of interest: "))

interest = calculate_simple_interest(principal, time, rate)
print(f"The Simple Interest is: {interest}")
