def valto(self):
    if self >= 41:
        return True
    else:
        return False


for _ in range(3):
    nev=input('Add meg a cipőt használó nevét! ')
    pont=int(input('Add meg a pontszámát! '))
    if valto(pont) == True:
        print(f'{nev} nagy lábon él.')
    else:
        print(f'{nev} kis lábon él.')