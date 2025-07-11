# Heights of students
john_height = 170
alice_height = 172
bob_height = 150

# Store in a dictionary for easy comparison
heights = {
    "John": john_height,
    "Alice": alice_height,
    "Bob": bob_height
}

# Find the tallest
tallest_student = max(heights, key=heights.get)

print(f"{tallest_student} is the tallest")
