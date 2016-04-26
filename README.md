# Text-Adventure
print ("INSTRUCTIONS")
print ("-When asked a yes no question reply with (y or n)")
print ("-when replying to a question with a full word use capital letters.")
print ("Welcome to the world of Eyou, where creatures of many forms wander the vast wastelands.")
print ("I am Kedo, your adventuring assistant for this journey across Eyou.")
print ("What's your name?")
name = input()
print ("So your name is",name,",cool!")
print ("You will have many choices on this adventure your first will be to open the door to either Aldspring or Dracbeach.")
print ("Which will you choose?")
place=input()
print ("Ahh, you wish to go to ",place,"great choice!")
if place=="Aldspring":
        print ("Beyond the door you find an abandoned hut masked with thick vines and foliage.")
        print ("Do you wish to adventure into the hut?")
        answer=input()
        if answer== "y":
            print ("You slowly step inside, and it pitch black you feel around for some kind of lantern and you find one, you light it and find a small lynx lying on the floor you bend down and stroke him and he slowly gets up he seems to like you, you decide to keep him, what do yo wish to name him?")
            lynx=input()
            print ("YOU OBTAINED A LYNX NAMED",lynx)
        else:
            print ("you walk past and find witch called Casandra she sees you and throws a potion out of her long winding coat do it smashes on the ground in front you, you become dizzy and fall over, do you wish to fight?")
            answer=input()
            if answer== "y": 
                print ("You throw a fist at the witches face, she catches it and forces a dagger through your chest!")
                print ("YOU DIED")       
    #Split between Locations
else:
        print ("You follow the path to Dracbeach, yet on your way you spot a small wolf stuck under a tree, you rescue it from underneath then he huddles close to your legs in a soft gentle manner.")
        # you obtain wolf
        print ("He seems to like you.")
        print ("You decide to keep him as he may be helpful along your journey")
        print ("What do you wish to name him?")
        wolf=input()
        print ("YOU OBTAINED A WOLF NAMED",wolf)





         

