START_GAME = input("Begin game? ")
SCORE = 0

if START_GAME.lower() != "yes":
    print("You have exited the game.")
    quit()
else:
    q1 = input("What is the first name of the man that created Java? ")
    if q1.lower() != "james":
        print("Incorrect answer. The correct answer is 'James' (last name Gosling).")
    else:
        print("CORRECT!")
        SCORE += 33
        q2 = input("What was the biggest search engine in 2000? ")
        if q2.lower() != "yahoo!":
            print("Incorrect answer. The correct answer is 'Yahoo!' (hint: purple with exclamation mark at the end).")
        else:
            print("CORRECT!")
            SCORE += 33
            q3 = input("What is the first programming language created? ")
            if q3.lower() != "assembly":
                print("Incorrect answer. The correct answer is 'Assembly' (hint: close to hardware with capital at start).")
            else:
                SCORE += 34
                print("CONGRADULATIONS YOU SCORED",SCORE,"OUT OF 100")
                quit()
