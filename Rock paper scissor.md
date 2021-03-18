```python
import random
import re
while (1 < 2):
    print("\n")
    print("Rock, Paper, Scissors - Shoot!")
    userChoice = input("Choose your weapon [R]ock], [P]aper, or [S]cissors: ")
    if not re.match("[SsRrPp]", userChoice):
        print("Please choose a letter:")
        print("[R]ock, [S]cissors or [P]aper.")
        continue
    
    print("You chose: " + userChoice)
    choices = ['R', 'P', 'S']
    opponenetChoice = random.choice(choices)
    print("I chose: " + opponenetChoice)
    if opponenetChoice == str.upper(userChoice):
        print("Tie! ")
    #if opponenetChoice == str("R") and str.upper(userChoice) == "P"
    elif opponenetChoice == 'R' and userChoice.upper() == 'S':      
        print("Rock beats scissors, I win! ")
        continue
    elif opponenetChoice == 'S' and userChoice.upper() == 'P':      
        print("Scissors beats paper! I win! ")
        continueS
    elif opponenetChoice == 'P' and userChoice.upper() == 'R':      
        print("Paper beat rock, I win! ")
        continue
    else:       
        print("You win!")
```

    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: S
    You chose: S
    I chose: S
    Tie! 
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: R
    You chose: R
    I chose: S
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: P
    You chose: P
    I chose: R
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: P
    You chose: P
    I chose: R
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: S
    You chose: S
    I chose: P
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: S
    You chose: S
    I chose: S
    Tie! 
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: P
    You chose: P
    I chose: R
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: P
    You chose: P
    I chose: R
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    Choose your weapon [R]ock], [P]aper, or [S]cissors: R
    You chose: R
    I chose: S
    You win!
    
    
    Rock, Paper, Scissors - Shoot!
    


```python

```
