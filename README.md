= int(input('Principal= '))
r= int(input('Rate%= '))
n= int(input('Period= '))
t= int(input('Compunded time= '))

ci= p*((1+(r/t)/100)**n*t)

print(ci)
