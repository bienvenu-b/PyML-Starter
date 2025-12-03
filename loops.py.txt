# loops.py

print("EXERCISE 1: Looping Through a List")

"""
Simple examples for practicing Python loops.
This script shows:
- looping through a list
- basic conditional logic
"""

# 1. A simple list of numbers
numbers = [1, 2, 3, 4, 5]

print("\n=== Numbers ===")
for number in numbers:
    print(number)

# 2. A list of climate seasons in Japan
seasons = ["spring", "summer", "fall", "winter"]

print("\n=== Climate Seasons in Japan ===")
for season in seasons:
    print(season.title())

print("\n" + "-" * 78)

print("\nEXERCISE 2: Conditional Logic in a Loop")

# A list of favorite cars
favorite_cars = ["jeep wrangler", "mercedes-benz", "tesla", "toyota"]

print("\n=== Car Messages ===")
for car in favorite_cars:
    if car == "jeep wrangler":
        print(f"{car.title()} is my first choice.")
    elif car == "toyota":
        print(f"{car.title()} has the greatest cost performance.")
    else:
        print(f"I like {car.title()} too.")
