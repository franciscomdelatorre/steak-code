# steak-code
python challenge: how to know if the steak is well done by temperature?
here's the code 

Temp = int(input('What is the steaks temperature (ºC)? '))

def ponto():
    if Temp < 48:
        print('Needs more cooking')
    elif Temp in range(48,53):
        print('Rare')
    elif Temp in range(54,59):
        print('Medium rare')
    elif Temp in range(60,64):
        print('Medium')
    elif Temp in range(65,71):
        print('Medium well')
    else:
        print('Well done')

ponto()
