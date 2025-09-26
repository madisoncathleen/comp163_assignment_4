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
