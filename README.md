# Oreck-Program
Oreck Quiz In Python
def main():
 yes_no = str(input('''Hello welcome to Oreck!
 Would you like to find out, which type of Oreck product you
resemble?
 Type Yes / No '''))
 if yes_no in("Yes", "yes") :
 variable = str(input("Are you an introvert or an extrovert?"))
 if variable in ("introvert", "extrovert"):
 per_1 = str(input('''Cool! Do you take your time to
find the best solution, or do you try
to get done as quickly and efficiently as possible?
Type "I take my time" or "I like to be quick." '''))
 if per_1 == "I take my time":
 print("You're an orbiter!")
 elif per_1 == "I like to be quick" or "quick":
 print("You are a handheld vacuum!")

 else:
 print("Feel free to come back later.")

 else:
 print("Feel free to come back later")
 count = 1
 while (count < 2):
 product = str(input('''What would you like to know about? We have Vacuums, Air Purifiers, Air Fresheners, and Orbiters '''))
 if product in ("orbiter", "Orbiter", "Orbiters", "orbiters"):
 print("You chose Orbiter!")
 elif product in ("Air Purifier", "air purifier", "Air
Purifiers"):
 print("You chose Air Purifier!")
 elif product in ("Vacuum", "vacuum", "Vacuums", "vacuums", "uum", "vac", "Vac"):
 #print("You chose Vacuum! Our vacuums are high quality.
Great choice!")
 type = str(input('''We have many different vacuums to
choose from. We have our Elevate Control,
Elevate Command, Elevate Conquer, Magnesium SP, and the Magnesium
RS, which one would you like to know about? '''))
 if type in ("Elevate Command", "elevate command"):
 print("You chose the elevate command! Excellent
pick.")
 elif type in ("Elevate Conquer", "elevate conquer",
"Elevate conquer"):
 print("You choose the Elevate Conquer! Good choice!")
 elif type in ("Elevate Control", "elevate control",
"Elevate control"):
 print("You choose the Elevate Control! Smart 
choice!")
 elif type in ("Magnesium RS", "magnesium RS", "Mag RS",
"Magnesium rs", "magnesium rs", "mag rs", "Mag rs"):
 print('''You chose the Magnesium RS! You think like
me! The lightest vacuum we have so
far at 7.7 lbs and the lowest profile. Get under your bed and toe
kicks in the kitchen''')
 elif type in ("Magnesium SP", "magnesium sp", "Magnesium
sp", "mag SP", "Mag SP", "mag sp", "Mag sp"):
 print("You chose the Magnesium SP! Smart choice!")
 else:
 print("Try typing it again")
 elif product in ("Air Fresheners", "air fresheners", "air
freshener", "Air Freshener"):
 print("Excellent choice! We have wonderful air
fresheners.")
 else:
 print("Oh boy. I'm just a silly program. I didn't get
that. Try typing it again.")

main()
