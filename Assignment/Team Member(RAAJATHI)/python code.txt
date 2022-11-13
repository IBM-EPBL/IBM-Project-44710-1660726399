from random import randint

humidity=randint(0,200)+1
temperature=randint(-200,200)+1
if humidity>100:
    print("humidity high")
    if temperature>100:
        print("temperature high")
