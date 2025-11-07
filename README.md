
dollar_rows = int(input("Please type the number of rows to print: "))
rows = ["$",
        "$$",
        "$$$",
         "$$$$", 
         "$$$$$"]
if dollar_rows == 1:
        print([rows[0]])
elif dollar_rows == 2:
        print([rows[0]])
        print([rows[1]])    
elif dollar_rows == 3:
        print([rows[0]])
        print([rows[1]])  
        print([rows[2]])
elif dollar_rows == 4:
        print([rows[0]])
        print([rows[1]])
        print([rows[2]])
        print([rows[3]])
elif dollar_rows == 5:
        print([rows[0]])
        print([rows[1]])
        print([rows[2]])
        print([rows[3]])
        print([rows[4]])
else:
  print( "Wrong input number try again.")
