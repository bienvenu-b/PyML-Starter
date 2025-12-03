# dictionaries.py

print("EXERCISE 1")

"""
Simple examples for practicing Python dictionaries.
This script shows:
- creating a dictionary
- adding new entries
- printing key–value information
"""

# A small dictionary of animals and their favorite breeds
favorite_animals = {
    "dog": "bulldog",
    "lion": "african lion",
}

print("\n=== Favorite Animals ===")
print(favorite_animals)

# Facts based on the current dictionary
print("\n=== Facts About Favorite Animals ===")
print(f"{favorite_animals['dog'].title()}s are famously good with children!")
print(f"The {favorite_animals['lion']} is often called the king of the jungle.")

# Add a new animal
favorite_animals["cat"] = "ragdoll"

print("\n=== Updated Favorite Animals ===")
print(favorite_animals)

# More facts after updating the dictionary
print("\n=== Additional Facts ===")
print(f"{favorite_animals['dog'].title()}s are famously good with children!")
print(f"The {favorite_animals['lion']} is often called the king of the jungle.")
print(f"{favorite_animals['cat'].title()}s are known for their calm and gentle nature.")

print("\n" + "-" * 78)

print("\nEXERCISE 2")

"""
Basic examples of looping through keys, values, and items in a dictionary.
This section shows:
- looping through keys
- looping through values
- looping through key–value pairs
"""

arsenal_players_and_numbers = {
    "saka": 7,
    "eze": 10,
    "odegaard": 8,
    "rice": 41,
    "trossard": 19,
}

print("\n--- Keys ---")
for player in arsenal_players_and_numbers:
    print(player.title())

print("\n--- Values ---")
for number in arsenal_players_and_numbers.values():
    print(number)

print("\n--- Key–Value Pairs ---")
for player, number in arsenal_players_and_numbers.items():
    print(f"{player.title()} wears number {number}.")
