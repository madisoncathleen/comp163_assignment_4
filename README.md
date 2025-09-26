# comp163_assignment_4

# note, this is the very very very basic examples i used to created another code that was 2k+ lines.
# >_<
# i dont wanna be yeeted for not following the rules though, so its only on zybooks.
# AI was used to help me bug fix, and understand some concepts better [CHATGPT]

current_gpa = 4.0         #voila we establishing some useless variables that'll have use soon
stress_level = 0
study_options = ["Programming", "Math", "English", "History"]
valid_courses = False
course_test = 'bruh'
social_points = 25
student_name = ("elvira") 
study_hours = 0
Programming = ''
Math ='' 

if current_gpa <= 2.1: # playing with the gpa variable to print different things with diff values
    print("Placeholder1")
elif 2.1 < current_gpa <= 3.8 or stress_level > 50: # making sure we're in a range for gpaand a simple less than 50 for our stress
    print("Placeholder2")
elif current_gpa >= 3.8:
    if study_options is not None and valid_courses: # checking if study options is blank and also that valid is true
        print("Placeholder 3")
        if "bruh" in course_test: # checks for that exact value inside of course_test
            print("bruh checked")
        else: print("Not Placeholder 3")
    elif course_test is None: # our course text is bruh right now and it isn't changing
        print("Impossible")
else:
    print ("Tests Done") #voila we have a nice example now!! 

    

#====================================



meowclass = input(f"\nTgo bunny go bunny: {study_options} ") 

if meowclass == "Programming":                             #changing other variables based on a singular variable
    print(f"programin bunny?\n{Programming}")            #AKA the bunny is going through his classes
    social_points = social_points + 5  
elif meowclass == "Math":
    print(f"quantum physics bunny seeks truth.. idk?\n{Math}")
    stress_level = stress_level + 10  
elif meowclass == "English":
    print("poem writing bunny!")
    current_gpa = current_gpa + 0.1  
elif meowclass == "History":
    print("whooshh history bunny")
    study_hours = study_hours + 2  
else:
    print("this is NOT a bunny class!")

print(" \n")


meowclass = input(f"\nthe smartest bunny must study Options: {study_options} ")

if meowclass == "Programming":
    print(f"oh my wow!!! who knew bunnies programmed\n{Programming}")
elif meowclass == "Math":
    print(f"bquantum physics bunny\n{Math}")
elif meowclass == "English":
    print("extra smart book bunny")
elif meowclass == "History":
    print("wowww time bunny")
else:
    print("no bunny")

print(" \n")

meowoutcome = ""

if current_gpa >= 3.5 and stress_level < 35:                    # changing outcomes based on variable values this time
    meowoutcome = "omg such cool bunny" 
elif current_gpa >= 3.0 and social_points >= 45:
    meowoutcome = "bunny smart and friendly"
elif current_gpa < 2.5 and stress_level > 70:
    meowoutcome = "stressed bunny"
elif social_points < 15:
    meowoutcome = "shy bunny"
else:
    meowoutcome = "do you even bunny fr, my guy?"
print(f"semesta outcome: {meowoutcome}")

if "Math" not in study_options:                     #an example of a 'not in' usage
    print("bunny lost the calculator :(")

 # me printing out all the stuff at like 4am on monday. ya its not monday anymore i just forgot the notes lol 
meowoutcome2 = {'pls spare me im so tired': student_name,'bunny gpa': current_gpa, 'bunny study': study_hours,'charizzma': social_points, 'stres': stress_level}
print(f"final warrior stuff idk bunny thing {meowoutcome2}")
