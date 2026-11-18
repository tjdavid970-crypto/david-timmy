print("===================================")
print("        PYTHON TUTORIAL            ")
print("===================================")
print("1 - prelim LESSON")
print("2 - Midterm LESSON")
print("3 - Final LESSON")
print("4 - PYTHON CHALLENGE")
print("0 - Exit")
print("===================================")

while True:
    choice = input("Select your topic: ")

    if choice == "1":
        print()
        print("Introduction to Python, Variables, Data Types, and Operators")
        print("Python is a programming language.")
        print("It is used to create programs and applications.")
        print()
        print("Example:")
        print("  print('Hello World')")
        print()
        print("Output:")
        print("  Hello World")
        print()
        print("---  BASIC PYTHON SYNTAX ---")
        print("Syntax means the rules of writing code.")
        print("Python uses indentation to organize code.")
        print()
        print("Example:")
        print("  print('i am learning python')")
        print()
        print("Output:")
        print("  i am learning python")
        print("Remember:")
        print("str = Text")
        print("int = Whole numbers")
        print("float = Decimal numbers")
        input("Press Enter to return to menu...")

    elif choice == "2":
        print()
        print("--- midterm LESSON ---")
        print("Lists and List Operations")
        print()
        print("A list stores multiple values.")
        print("Items are placed inside square brackets.")
        print()
        print("Variables store information.")
        print()
        print("Example:")
        print("  name = 'jumong'")
        print("  age = 16")
        print("  print(name)")
        print("  print(age)")
        print()
        print("Output:")
        print(" jumong ")
        print("  16  ")
        print()
        print("List Operations:")
        print("append() = Adds an item")
        print("remove() = Removes an item")
        print("len() = Counts the items")
        input("Press Enter to return to menu...")
    elif choice == "3":
        print()
        print("--- final LESSON ---")
        print("Operators are used to perform operations.")
        print()
        print("Examples:")
        print("  3 + 4 = 7")
        print("  4 - 5 = 1")
        print("  5 * 5 = 25")
        print("  10 / 2 = 5")
        print("Loops repeat a block of code.")
        print("There are two common types of loops:")
        print()
        print("WHILE LOOP:")
        print("Repeats while a condition is true.")
        print()
        print("Python Code:")
        print("count = 1")
        print("while count <= 3:")
        print("    print(count)")
        print("    count += 1")
        print()
        print("FOR LOOP:")
        print("Repeats through a sequence or range.")
        input("Press Enter to return to menu...")

    elif choice == "4":
        print()
        print("========= SHORT QUIZ =========")
        score = 0

        print("1. What is Python?")
        print("A. computer")
        print("B. Programming language")
        print("C. language")
        answer = input("Your answer: ").upper()
        if answer == "B":
            score += 1

        print()
        print("2. What is the purpose of print() in Python??")
        print("A. to display")
        print("B. to delete files")
        print("C. to stop the program")
        answer = input("Your answer: ").upper()
        if answer == "A":
            score += 1

        print()
        print("3. What stores information?")
        print("A. Variable")
        print("B. Operator")
        print("C. Function")
        answer = input("Your answer: ").upper()
        if answer == "A":
            score += 1

        print()
        print("4. What is 10 + 10?")
        print("A. 10")
        print("B. 20")
        print("C. 30")
        answer = input("Your answer: ").upper()
        if answer == "B":
            score += 1

        print()
        print("5 Which function outputs text to the screen in Python?")
        print("A. display")
        print("B. print")
        print("C. echo")
        answer = input("Your answer: ").upper()
        if answer == "B":
            score += 1

        print()
        print("========= QUIZ RESULT =========")
        print("Your score:", score, "/ 5")

        if score == 4:
            print("nice!")
        elif score >= 2:
            print("Good keep it up! Keep practicing.")
        else:
            print("study hard and try again.")

        input("Press the Enter to return to menu...")

    elif choice == "0":
        print("Arigato sir1 for learning Python!")
        break

    else:
        print("your choice is invalid!")
