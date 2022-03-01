#-------------------------------------------------------------------------------
# Name: Afomya Sisay Alemayehu
# Assignment 3
# Due Date:02/28/2022
#-------------------------------------------------------------------------------
# Honor Code Statement: I received no assistance on this assignment that
# violates the ethical guidelines set forth by professor and class syllabus.
#-------------------------------------------------------------------------------
# References: (W3W)
#-------------------------------------------------------------------------------
# Comments and assumptions: A note to the grader as to any problems or
# uncompleted aspects of the assignment, as well as any assumptions about the
# meaning of the specification.
#-------------------------------------------------------------------------------
# NOTE: width of source code should be <=80 characters to be readable on-screen.
#2345678901234567890123456789012345678901234567890123456789012345678901234567890
# 10 20 30 40 50 60 70 80
#-------------------------------------------------------------------------------


# I used the pre-defined function provided
def break_time(hours_worn, last_break):
    result = 0
    # as long as we get a float when we divide
    # hours worn with last break, Ill run the
    # function
    while hours_worn % last_break != 0:
        # I add 1 to the result each time the above
        # while loop is satisfied
        result += 1
        # This is to convert the quotient to an integer
        hours_worn = hours_worn // last_break

    return result


# I used the pre-defined function provided
def how_many_uruks(strength_values, init_fund_needed):
    result = 0
    budget = 0
    for value in strength_values:
        # if the value isn't 0 and is even
        # we multipy for each value of strength_values
        if value != 0 and value % 2 == 0:
            budget *= value
        # otherwise, we add for each value of strength_values
        else:
            budget += value
    # as long as the budget is greater than the initial
    # fund needed, we can keep subtracting from
    # the budget in the incrementing values of initial
    # fund needed
    while budget >= init_fund_needed:
        budget = budget - init_fund_needed
        init_fund_needed += 1
        result += 1

    return result


# I used the pre-defined function provided
def years_to_rule(n1, n2, n3):
    result = 0
    computation = 0
    # for every value between 1 and n1
    for t in range(1, n1 + 1):
        # and for every value between 1 and n2
        for l in range(1, n2 + 1):
            # we multiply each of those values by each other
            # and then we divide each one by n3
            computation = (t * l) // n3
            # then we add up all of the values together 
            # and that is our result
            result += computation
    return result


# I used the pre-defined function provided
def lotr_popularity(char_list):
    popularity = 0
    character = 0
    counter = 0
    gandalf = 0
    aragorn = 0
    legolas = 0

    # we pull out every character on the char_list
    for character in char_list:
        # if gandalf in char_list, we add 10 to the popularity
        # rating and add 1 to gandalf for most appeared
        if character == "Gandalf":
            popularity += 10
            gandalf += 1
        # if aragorn in char_list, we add 20 to the popularity
        # rating and add 1 to aragorn for most appeared
        elif character == "Aragorn":
            popularity += 20
            aragorn += 1
        # if legolas in char_list, we add 5 to the popularity
        # rating and add 1 to legolas for most appeared
        elif character == "Legolas":
            popularity += 5
            legolas += 1

        else:
            popularity += 0

    if gandalf > aragorn and gandalf > legolas:
        character = "Gandalf"
    if aragorn > gandalf and aragorn > legolas:
        character = "Aragorn"
    if legolas > gandalf and legolas > aragorn:
        character = "Legolas"

    result = "Most Appeared: " + character + ", Popularity: " + str(popularity)
    return result




