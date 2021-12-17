enter_code = str(input("Enter here: "))
verify_two = str(input("Who sent you the code: "))
name_input = str(input("What is your name: "))
server_link = "https://discord.gg/sKc8wHMn"

if enter_code == "skeleton":
    verify_two
    if verify_two == "CHEESE":
        name_input
        server_link
    elif verify_two == "Amogus":
        name_input
        server_link
    elif verify_two == "TheSecretCode":
        name_input
        server_link
    else:
        print("You are not yet allowed to join the server, if you think you made a typo, please try again")
elif enter_code == "CHEESE":
    print("Welcome CHEESE to the server!"+server_link)
elif enter_code == "Amogus":
    print("Welcome Amogus to the server!"+server_link)
else:
    print("You are not yet allowed to join the server, if you think you made a typo, please try again")
