rooms = {
    "A": "Dirty",
    "B": "Dirty"
}

room = "A"

while True:
    print("\nRoom:", room)
    print("Status:", rooms[room])

    if rooms[room] == "Dirty":
        print("Cleaning room...")
        rooms[room] = "Clean"
    else:
        print("Room is already clean.")

    if room == "A":
        room = "B"
    else:
        room = "A"

    choice = input("Continue? (y/n): ")

    if choice.lower() != "y":
        break

print("Vacuum cleaner stopped.")
