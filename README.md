A simple Python program to calculate the speed of a car given the distance traveled and the time taken

# Car-Speed-Distance-Time
 # Function to calculate speed
def calculate_speed(distance, time):
    if time > 0:
        speed = distance / time
        return speed
    else:
        return "Time must be greater than 0 to calculate speed."

# Example inputs for distance (in kilometers) and time (in hours)
distance = float(input("Enter the distance traveled (in kilometers): "))
time = float(input("Enter the time taken (in hours): "))

# Calculate speed
speed = calculate_speed(distance, time)

print(f"The speed of the car is {speed} km/h")

