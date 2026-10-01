#I've finally learned how to make my own quiz game !!!
#well not technically my own, but i just edited bro codes code into my own stuff...Hope you like it XD

questions = (
"Who is the main character in Naruto ",
"How many Dragon balls are required to summon Shenron ",
" Devil fruit users can't :______",
"The Power system in Hunter x Hunter is :___ ",
"_____ is the strongest jujutsu sorcerer in history ",
"______ is the strongest Sorcerer in the modern age  ",
"Ichigo Kurosaki's blade is called ?' ",
"Who is Bardock  ?",
"Blue Lock's Main character is : ",
"Which of the following is Luffy From ")

options = (
    ("A. Goku", "B. Naruto", "C. Luffy", "D. Ichigo"),
    ("A. 4", "B. 6", "C. 7", "D. 10"),
    ("A. Swim", "B. Eat other fruits", "C. Bath", "D. Fish"),
    ("A. Cursed energy", "B. Ki", "C. Chakra", "D. Nen"),
    ("A. Ryomen Sukuna", "B. Gojo Satoru", "C. Goku", "D. Saitama"),
    ("A. Geto Suguru", "B. Gojo Satoru", "C. Ryomen Sukuna", "D. Yuta Okkotsu"),
    ("A. Utahime", "B. Bankai", "C. Zangetsu", "D. Goku"),
    ("A. Goku's son", "B. Goku's Mother", "C. Goku's Father", "D. Your Father"),
    ("A. Isagi", "B. Gin Ichimaru", "C. Saitama", "D. Mob"),
    ("A. Black Clover", "B. Blue Lock", "C. One Piece", "D. One Piece")
)

answers = (("B"),("C"),("A"),("D"),("A"),("B"),("C"),("C"),("A"),("D"),)

guesses = []
score = 0
question_num = 0

for question in questions :
	print("--------")
	print(question)
	for option in options[question_num] :
			print(option)
	guess = input("Enter A,B,C or D : ")
	guess = guess.upper()
	guesses.append(guess)
	
	if guess == answers[question_num] :
		score += 1 
		print("Correct !!")
	else :
		print("Incorect")
		print(f"The correct answer is {answers[question_num]}")
	question_num += 1

total = (score / len(questions)) * 100
print("=" * 15,"Results","=" * 15)
print(f"Your score is {total}%")
print("=" * 37)


	
	
    

	 
	
		

	  

 
	  


	  

