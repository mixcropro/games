#rock paper sisor
import random
print("ROCK, PAPER, SCISSORS")
win, lose, tie = 0, 0, 0
counter = 0
rounds = random.randint(3,10)
print("Enter your move: (r)ock (p)aper (s)cissor or (q)uit")
while counter < rounds:
    p1 = input("First player: ")
    p2 = random.choice("rps")
    if p1 == "q":
        break
    elif p1 == p2:
        print("You and computer chose the same " + p2)
        tie += 1
        counter +=1
        continue
    elif p1 == "r" and p2 == "p":
        print("You chose rock but computer chose "+p2)
        lose +=1
        counter += 1
        continue
    elif p1 =="r" and p2 == "s":
        print ("You chose rock and computer chose " + p2)
        win += 1
        counter += 1
        continue
    elif p1 == "p" and p2 =="r":
        print ("You chose paper and computer chose " + p2)
        win += 1
        counter += 1
        continue
    elif p1 == "p" and p2 == "s":
        print ("You chose paper but computer chose " + p2)
        lose += 1
        counter += 1
        continue
    elif p1 == "s" and p2 == "p":
        print ("You chose scissor and computer chose " + p2)
        win += 1
        counter += 1
        continue
    elif p1 == "s" and p2 == "r":
        print ("You chose scissor and computer chose " + p2)
        lose += 1
        counter += 1
        continue
print("You have "+ str(win) +" wins "+str(lose)+" loses and "+str(tie)+" ties "+" and you played "+ str(counter)+ " rounds!" )
