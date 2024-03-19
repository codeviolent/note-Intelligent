notes=[]
notes_input=input("de5el lme3loumet  ")  
notes.append(notes_input)
while notes_input in notes:
    notes_2=notes
    for x in notes_2:
       if x in notes_input:
         print(f"-{x}\n") 
    notes_input=input("de5el lme3loumet  \n") 
    if notes_input not in notes:
        print("ha4i mh houn")
        notes_inp=input("dor tsejelhe ? \n ") 
        if notes_inp=="oui":
          notes_input=input("sejelhe \n") 
          notes.append(notes_input)
