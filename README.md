
print(' Welcome to my computer game ! 🎲 ')

p = input('Do you want to play ? ')

if p != 'yes' :
    quit()
print('okey  let´s play ☺️ ! ')
score = 0

a = input(' Why do we using the camera ?')
if a.lower()== 'for taking pictures' :
    print('correct.')
    score +=1
else :
    print('incorrect !')

a = input(' Why do we using İnshot app ?')
if a.lower()== 'for editing videos and photos' :
    print('correct.')
    score +=1
else :
    print('incorrect !')
    
a = input(' Why do we using wattsapp ?')
if a.lower()== 'for chatting with others' :
    print('correct.')
    score +=1
else :
    print('incorrect !')
    
print('you got' +  str( score ) +  'correct questions !' )
print('you got' +  str( (score /3) * 100 ) +  '%.' )
