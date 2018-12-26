# Meme-Quiz
Python
print("                   WELCOME TO MEME QUIZ")
a=input("Enter your Name: ")
print("\na Let's Start the Quiz")
score=0
question1 = "1) Who is president of USA?"
options1 = "a. Myslef\nb. Narendra Modi\nc. Kumaraswamy\nd. Donald Trump\n"
print("\n",question1)
print(options1)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "d":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "d":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break
question2 = "2) The longest river in world?"
options2 = "a. Nile\nb. Kengeri\nc. Kaveri\nd. Nethravathi\n"
print("\n",question2)
print(options2)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "a":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "a":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break

question3 = "3) The world's oldest known city?"
options3 = "a. Electronic city\nb. Silicon city\nc. Damascus\nd. Mumbai\n"
print("\n",question3)
print(options3)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "c":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "c":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break

question4 = "4) Biggest delta in the world?"
options4 = "a. Ganges delta\nb. Star delta\nc. Gilbert delta\nd. Inland delta\n"
print("\n",question4)
print(options4)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "a":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "a":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break
question5 = "5) The worlds largest diamond producing country?"
options5 = "a. India\nb. England\nc. America\nd. South Africa\n"
print("\n",question5)
print(options5)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "d":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "d":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break

question6 = "6) When was PESIT was established?"
options6 = "a. 1947 \nb. 2005 \nc. 2018 \nd. 1972\n"
print("\n",question6)
print(options6)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "b":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "b":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break
question7 = "7) Who's daddy agreed to gives us space for internet?"
options7 = "a. Mydaddy\nb. Godaddy\nc. My uncle's Daddy\nd. Super Daddy\n"
print("\n",question7)
print(options7)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "b":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "b":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break
question8 = "8) Which of the following book is famous all over the world?"
options8 = "a. Arts Book\nb. Science Book\nc. Facebook\nd. Commerce Book\n"
print("\n",question8)
print(options8)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "c":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "c":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break
question9 = "9) Which is the most expensive gate?"
options9 = "a. Colgate\nb. Bill gates\nc. Electronic gate\nd. Machine gate\n"
print("\n",question9)
print(options9)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "b":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "b":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break
question10 = "10) Which of the following table you can eat?"
options10 = "a. Dining Table\nb. Computer table\nc. Vegetable\nd. All of these\n"
print("\n",question10)
print(options10)

while True:
    response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

    if response == "c":
        score+=1
        break
    else:
        print("Incorrect!!! Try again.")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "c":
                stop = True
                score+=1
                break
            else:
                print("Incorrect!!! You ran out of your attempts")
                stop = True
                break
        if stop:
            break



while True:
    bonus = input("\n Would you like to give a try to the bonus question?\nHit 'y' for yes and 'n' for no.\n")

    if bonus == "y":
        print("Man to score fastest 10,000 runs in ODI?")
        print("a. Me\nb. Sachin Tendulkar\nc. Virat Kohli\nd. Kishore Reddy")

        while True:
            response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")

            if response == "c":
                break
            else:
                print("Incorrect!!! Try again.")

            while True:
                response = input("Hit 'a', 'b', 'c' or 'd' for your answer\n")


                if response == "c":
                    stop = True
                    break
                else:
                    print("Incorrect!!! You ran out of your attempts")
                    stop = True
                    break
            if stop:
                break
        break
    elif bonus == "n":
        break
    else:
        print("INVALID INPUT!!! Only hit 'y' or 'n' for your response")
print('Hey', a , 'you have finished and scored', score, 'out of 10')
print("Hope You Enjoyed!!")
a=input("       Share your feedback        \n")
print("Thank You.")
