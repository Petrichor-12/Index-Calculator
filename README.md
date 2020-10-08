# Index-Calculator
\\NASA International Space Apps Challenge, Nepal\\
print('WELCOME TO PETRICHOR INDEX CALCULATOR')
print('Please respond to following questions')
import numpy as np
B = input('How long you walked or bicycled instead of using vehicle(in kilometer) = ')
B = int(B)*10
D = input('Did you volunteer an environmental campaign or program = ')
if D == 'Yes':
    D = 10
else:
    D = 0
E = input('do you recycled your non-degradable waste instead of throwing it away ? =')
if E == 'Yes':
    E = 10
else:
    E =10
F = input('Do you have eco friendly light bulbs at your home ? = ')
if F == 'Yes':
    F = 10
else:
    F = 0
G = input('The number of trees you planted this week = ')
G = 10*int(G)
H = input('Did you avoided use of plastic bags during this week ? = ')
if H == 'Yes':
    H = 10
else:
    H = 0
X = np.log(int(B)+int(D)+ int(E)+int(F)+int(G)+int(H))
print('your weekly index = ', int(X),\
     ',Congratulations, you have contributed for saving our planet')
