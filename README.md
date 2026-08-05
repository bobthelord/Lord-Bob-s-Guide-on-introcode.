# Lord-Bob-s-Guide-on-introcode.
# Sorting using lambda


  # Sorts in ascending order


students = [


    ("John",60),
    ("Peter",90),
    ("Bob",80),

]

students.sort(key=lambda x:x[1])
print(students)


  # Sorts in descending order
students = [

    ("John",60),
    ("Peter",90),
    ("Bob",80),

]

students.sort(key=lambda x:x[1], reverse=True)
print(students)


    # Print only student in alphabetical order

students = [


    ("John",60),
    ("Peter",90),
    ("Bob",80),

]

students.sort()
            # use one of both or use both
print(students)


