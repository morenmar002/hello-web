run_prog = True

print("\033[1mWelcome to Hogwarts, School of Witchcraft and Wizardry\033[0m ")
input("\033[3mpress enter to continue\033[0m")
print("")
print("Hogwarts is home to all witches and wizards near Scotland. Founded in 990 A.D. by Godric Gryffindor, Salazar Slytherin, Helga Hufflepuff, and Rowena Ravenclaw.")
input("\033[3mpress enter to continue\033[0m")
print("")



while run_prog == True:

    menu_choice = input("\033[1mtype 1 to learn about Hogwarts, type 2 to learn about Hogwarts' houses, type 3 to learn about the author of the Harry Potter series, J.K. Rowling, type 4 to learn about the main character, or type 5 to read a breif summary of each book. To end the program, type end. Press enter to finalize your choice.\033[0m")

    if menu_choice == "1":
        print("")
        print("\033[4mHogwarts\033[0m")
        print("")
        print("")
        print("Hogwarts is a fictional school in the famous Harry Potter series. It is a school for children ages 11-18 that enroll to further their magical studies as future wizards and witches. The series takes place in the school most of the time, focusing on the main character... Harry Potter, and his friends: Hermione Granger and Ron Weasley.")
        print("")
        input("\033[3mpress enter to continue\033[0m")
        print("") 

    if menu_choice == "2":
        print("")
        print("\033[4mHogwarts Houses\033[0m")
        print("")
        print("")
        print("Students who enter Hogwarts are first seperated into 4 houses: Gryffindor, Ravenclaw, Slytherin, and Hufflepuff.")
        print("")
        print("\033[31mGryffindor qualities include courage, chivalry, bravery and can also be considered as short-tempered.\033[0m")
        print("")
        print("\033[34mRavenclaws can be described as creative, witty, and are often the most intelligent and studious.\033[0m")
        print("")
        print("\033[32mSlytherin is seen as cunning, ambitious, shrewd, and clever.\033[0m")
        print("")
        print("\033[33mThe last house is Hufflepuff, known for their patience and loyalty to others.\033[0m")
        print("")

    if menu_choice == "3": 
        print("\033[4mJ.K. Rowling\033[0m")
        print("")
        print("Known as Joanne Kathleen Rowling, a british female author most famous for her writing on Harry Potter wrote seven books that made the series. Her seven books were: Harry Potter and the Sorcerer's Stone, Harry Potter and the Chamber of Secrets, Harry Potter and the Prisoner of Azkaban, Harry Potter and the Goblet of Fire, Harry Potter and the Order of the Phoenix, Harry Potter and the Half-Blood Prince, and Harry Potter and the Deathly Hallows. ")
        input("\033[3mpress enter to continue\033[0m")
        print("")
    
    if menu_choice == "4":
        print("\033[4mHarry Potter\033[0m")
        print("")
        print("Harry Potter is the main character in the series, he is famously known for beating the antagonist, Voldemort, more than once. He lived an abusive childhood with his aunt and her family. The series creates a story of Harry's life and how he navigates through hardships and times of peril. He journeys through Hogwarts along with his two best friends, until they graduate.")
        print("")

    if menu_choice == "5":
        print("")
        print("\033[4mHarry Potter and the Sorcerer's Stone\033[0m")
        print("Harry Potter is an orphan left to the care of his aunt and her family. As a young boy he experiences being different and isolated from others. Later, he discovers that he is a wizard and enrolls into a english boarding school for magical beings. Being a sheltered eleven year old boy, he discovers many things about the wizarding world, his family, and his history.")
        print("")
        print("\033[4mHarry Potter and the Chamber of Secrets\033[0m")
        print("The second book to the series, Harry Potter meets a mysterious elf that risks his elegibility to go to Hogwarts. Throughout his second year there, he witnesses strange writing on the wall, flying cars, and spiders that can talk. This all leads to one thing, the chamber of secrets.")
        print("")
        print("\033[4mHarry Potter and the Prisoner of Azkaban\033[0m")
        print("Harry's third year at Hogwarts leads to more trouble than ever, he learns that Sirius Black has escaped from one of the most impenetrable prisons of all, Azkaban. It's rumored that Sirius was going to kill Harry, and has to learn to defend himself with the help of his Defence Against the Dark Arts teacher.")
        print("")
        print("\033[4mHarry Potter and the Goblet of Fire\033[0m")
        print("Harry Potter is mysteriously entered into a tournament made for older students. Albeit he did not enter it willingly, he is forced to play and complete the dangerous, even life threatening tasks. This all leads to his one enemy, Voldemort.")
        print("")
        print("\033[4mHarry Potter and the Order of the Phoenix\033[0m")
        print("Things are taking a rough turn at Hogwarts. Many non-muggles are being lied to about the upcoming evil that's about to come, Voldemort. Harry and his two friends try to fight back but encounter their new Defence against the Dark Arts teacher, Dolores Umbridge. A representative of the ministry, she makes going to school a living hell with her cruel methods.")
        print("")
        print("\033[4mHarry Potter and the Half-Blood Prince\033[0m")
        print("As the magical world becomes more dangerous and viulnerabel to Voldemort, death eaters surround the worlds... both muggle and non-muggle. Hogwarts is not a safe place anymore and all students must learn to protect and defend themselves from evil. ")
        print("")
        print("\033[4mHarry Potter and the Deathly Hallows\033[0m")
        print("After Dumbledore's tragic death, Harry, Hermione, and Ron must learn how to defeat Voldemort once and for all. They learn of a children's tale, the Deathly Hallows. Could this help them defeat him?")
        print("")

   
    elif menu_choice == "end":
        run_prog = False

print("Thank you! Goodbye.")



