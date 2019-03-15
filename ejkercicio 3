%% Problema 1
syms x a b y c
eqn = 2*x+a;
A = solve(eqn==5, x)
AA = subs(eqn,[a x],[1 2])

%% Problema 2
syms x a b y c
eqn = x^2+a*x+b;
BB = subs(eqn,[a b],[3 2])
B = solve(BB==0, x)
subs(eqn,[a b x], [3 2 -2])

%% Problema 3

syms x a b y c
eqn = 2*exp(x)+3*cos(x);
CC = subs(eqn,x,1)
C = vpa(CC)

%% Problema 4

syms a b c x y 
eqn = 2*x-3*c*y;
eqn2 = c*x+2*y;
D1 = subs(eqn, c, 2);
D2 = subs(eqn2, c, 2);
D = solve([D1==5,D2==7], [x,y]);
DX=D.x
DY=D.y 

%% Problema 5

syms a b c x y 
eqn = 3*x^2-2*x+y;
eqn2 = x*y+x;
E = solve([eqn==7,eqn2==5], [x,y]);
EX=E.x
EY=E.y 
