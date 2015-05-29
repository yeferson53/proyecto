# proyecto
from turtle import*
speed(9)
pensize(2)
pu()
goto(-200,-200)

goto(-200,200)
pd()
forward(300)
right(90)
forward(300)
right(90)
forward(300)
right(90)
forward(300)
right(90)
forward(100)
right(90)
forward(300)
pu()
lt(90)
forward(100)
lt(90)
pd()
forward(300)
pu()
goto(-200,100)
pd()
right(90)
forward(300)
pu()
goto(-200,0)
pd()
forward(400)
right(90)
forward(100)
right(180)
forward(300)
right(270)
forward(100)
right(270)
forward(100)
right(270)
forward(100)
right(90)
forward(300)
right(90)
forward(400)
right(90)
forward(100)
right(90)
forward(100)
right(90)
forward(100)
right(270)
forward(100)
right(270)
forward(100)
right(90)
forward(100)
right(270)
forward(100)
right(180)
forward(100)
right(270)
forward(100)
right(180)
forward(100)
right(270)
forward(100)
pu()

def triqui():
    "Juego De Triqui De Cuatro Lineas"
    k=[["-","-","-","-"],
       ["-","-","-","-"],
       ["-","-","-","-"],
       ["-","-","-","-"]]
    l=0
    while l <= 7:
            p=0
            s=0
            while p < 1:
                i=(int(input("Jugador 1: Diga En Que Fila Quiere Poner Su Simbolo: ")))
                j=(int(input("Jugador 1: Diga En Que columna Quiere Poner Su Simbolo: ")))
                k[i][j]="X"
                p = p + 1
                print(k)
                if k[0][0] == "X" and k[0][1] == "X" and k[0][2] == "X" and k[0][3] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[1][0] == "X" and k[1][1] == "X" and k[1][2] == "X" and k[1][3] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[2][0] == "X" and k[2][1] == "X" and k[2][2] == "X" and k[2][3] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[3][0] == "X" and k[3][1] == "X" and k[3][2] == "X" and k[3][3] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][0] == "X" and k[1][0] == "X" and k[2][0] == "X" and k[3][0] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][1] == "X" and k[1][1] == "X" and k[2][1] == "X" and k[3][1] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][2] == "X" and k[1][2] == "X" and k[2][2] == "X" and k[3][2] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][3] == "X" and k[1][3] == "X" and k[2][3] == "X" and k[3][3] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][0] == "X" and k[1][1] == "X" and k[2][2] == "X" and k[3][3] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][3] == "X" and k[1][2] == "X" and k[2][1] == "X" and k[3][0] == "X":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][0] == "O" and k[0][1] == "O" and k[0][2] == "O" and k[0][3] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[1][0] == "O" and k[1][1] == "O" and k[1][2] == "O" and k[1][3] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[2][0] == "O" and k[2][1] == "O" and k[2][2] == "O" and k[2][3] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[3][0] == "O" and k[3][1] == "O" and k[3][2] == "O" and k[3][3] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][0] == "O" and k[1][0] == "O" and k[2][0] == "O" and k[3][0] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][1] == "O" and k[1][1] == "O" and k[2][1] == "O" and k[3][1] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][2] == "O" and k[1][2] == "O" and k[2][2] == "O" and k[3][2] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][3] == "O" and k[1][3] == "O" and k[2][3] == "O" and k[3][3] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][0] == "O" and k[1][1] == "O" and k[2][2] == "O" and k[3][3] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif k[0][3] == "O" and k[1][2] == "O" and k[2][1] == "O" and k[3][0] == "O":
                    print ("El Jugador 1 Es El Ganador")
                elif l==7:
                    print("No Hay Ganador")
            while s < 1:
                i=(int(input("Jugador 2: Diga En Que Fila Quiere Poner Su Simbolo: ")))
                j=(int(input("Jugador 2: Diga En Que columna Quiere Poner Su Simbolo: ")))
                k[i][j] = "O"
                s = s + 1
                print(k)
                if k[0][0] == "X" and k[0][1] == "X" and k[0][2] == "X" and k[0][3] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[1][0] == "X" and k[1][1] == "X" and k[1][2] == "X" and k[1][3] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[2][0] == "X" and k[2][1] == "X" and k[2][2] == "X" and k[2][3] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[3][0] == "X" and k[3][1] == "X" and k[3][2] == "X" and k[3][3] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][0] == "X" and k[1][0] == "X" and k[2][0] == "X" and k[3][0] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][1] == "X" and k[1][1] == "X" and k[2][1] == "X" and k[3][1] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][2] == "X" and k[1][2] == "X" and k[2][2] == "X" and k[3][2] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][3] == "X" and k[1][3] == "X" and k[2][3] == "X" and k[3][3] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][0] == "X" and k[1][1] == "X" and k[2][2] == "X" and k[3][3] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][3] == "X" and k[1][2] == "X" and k[2][1] == "X" and k[3][0] == "X":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][0] == "O" and k[0][1] == "O" and k[0][2] == "O" and k[0][3] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[1][0] == "O" and k[1][1] == "O" and k[1][2] == "O" and k[1][3] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[2][0] == "O" and k[2][1] == "O" and k[2][2] == "O" and k[2][3] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[3][0] == "O" and k[3][1] == "O" and k[3][2] == "O" and k[3][3] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][0] == "O" and k[1][0] == "O" and k[2][0] == "O" and k[3][0] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][1] == "O" and k[1][1] == "O" and k[2][1] == "O" and k[3][1] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][2] == "O" and k[1][2] == "O" and k[2][2] == "O" and k[3][2] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][3] == "O" and k[1][3] == "O" and k[2][3] == "O" and k[3][3] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][0] == "O" and k[1][1] == "O" and k[2][2] == "O" and k[3][3] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif k[0][3] == "O" and k[1][2] == "O" and k[2][1] == "O" and k[3][0] == "O":
                    print ("El Jugador 2 Es El Ganador")
                elif l==7:
                    print("No Hay Ganador")
                s=s+1
            l=l+1
        

def estrategia():
    "Crea Una Estrategia Personalizada Del Jugador"
    t=0
    enemigo=[]
    enemigo2=[]
    personal=[]
    personal2=[]
    u=input("Â¿Su Contrincante Son Las O Ã² las X?(Nota: Recuerde Poner Las Comillas Y Mayuscula): ")
    W=int(input("Â¿Cuantas Estrategias Creara?: "))
    while t < W:
        d=0
        s=0
        while s < 1:
            M=0
            N=0
            B=0
            V=0
            y=int(input("En Que fila El Jugador 2 Debe Poner Su Simbolo Para La Estrategia 1: "))
            while y > 16 and y < 0 and M < 1:
                print("Error, Ingrese Un Numero De 0 a 16")
                M=M+1
            v=int(input("En Que Columna El Jugador 2 Debe Poner Su Simbolo Para La Estrategia 1: "))
            while v > 16 and v < 0 and M < 1:
                print("Error, Ingrese Un Numero De 0 a 16")
                N=N+1
            i=int(input("Diga En Que fila Quiere Poner Su Simbolo Para La Estrategia 1: "))
            while i > 16 and i < 0 and M < 1:
                print("Error, Ingrese Un Numero De 0 a 16")
                B=B+1
            j=int(input("Diga En Que columna Quiere Poner Su Simbolo Para La Estrategia 1: "))
            while j > 16 and j < 0 and M < 1:
                print("Error, Ingrese Un Numero De 0 a 16")
                V=V+1
            enemigo2.append((y,v))
            enemigo2.append(v)
            personal2.append(i)
            personal2.append(j)
            enemigo.append(enemigo2)
            personal.append(personal2)
            s=s+1
        print(enemigo)
        print(personal)
        if u == "X":
            while d < len(personal):
                peronal[i][j]= "O"
                d = d + 1
        if u == "O":
            while d < len(personal):
                peronal[i][j]= "X"
                d = d + 1
        t=t+1
def juego_triqui():
    g=input("Nombre Del Jugador 1: ")
    f=input("Nombre Del Jugador 2: ")
    a=0
i=1
n1=0
n2=0
n3=0
n4=0
n5=0
n6=0
n7=0
n8=0
n9=0
n10=0
n11=0
n12=0
n13=0
n14=0
n15=0
n16=0
sw=0
while i <=16:
    if i<17:
        n=numinput('','Ingrese La Posicion Donde Quiere La X')   
        if n == 1:
            goto(-160,130)
            write('x',font = ("arial",40,"bold"))
            n1=2
        if n ==2:
            goto(-60,130)
            write('x',font = ("arial",40,"bold"))
            n2=2
        if n ==3:
            goto(40,130)
            write('x',font = ("arial",40,"bold"))
            n3=2
        if n ==4:
            goto(140,130)
            write('x',font = ("arial",40,"bold"))
            n4=2
        if n ==5:
            goto(-160,30)
            write('x',font = ("arial",40,"bold"))
            n5=2
        if n ==6:
            goto(-70,30)
            write('x',font = ("arial",40,"bold"))
            n6=2
        if n ==7:
            goto(40,30)
            write('x',font = ("arial",40,"bold"))
            n7=2
        if n ==7:
            goto(-160,-70)
            write('x',font = ("arial",40,"bold"))
            n7=2
        if n ==8:
            goto(-60,-70)
            write('x',font = ("arial",40,"bold"))
            n8=2
        if n ==9:
            goto(40,-70)
            write('x',font = ("arial",40,"bold"))
            n9=2
        i= i +1
    if n1==2 and n4==2 and n7==2 and sw ==0:
        goto(-150,200)
        rt(90)
        pd()
        fd(300)
        i=10
        sw=1
        write('!!!TRIKI!!!!!',font=('arial',50,'bold'))
    if n1==2 and n2==2 and n3==2 and sw ==0:
        goto(-200,150)
        pd()
        fd(300)
        i=10
        sw=1
    if n1==2 and n5==2 and n9==2 and sw ==0:
        goto(-200,200)
        pd()
        rt(45)
        fd(430)
        i =10
        sw=1
    if n4==2 and n5==2 and n6==2 and sw ==0:
        goto(-200,50)
        pd()
        fd(300)
        i=10
        sw=1
    if n7==2 and n8==2 and n9==2 and sw ==0:
        goto(-200,-50)
        pd()
        fd(300)
        i=10
        sw=1
    if n2==2 and n5==2 and n8==2 and sw ==0:
        goto(-50,200)
        rt(90)
        pd()
        fd(300)
        i=10
        sw=1
    if n3==2 and n6==2 and n9==2 and sw ==0:
        goto(50,200)
        rt(90)
        pd()
        fd(300)
        i=10
        sw=1
    if n3==2 and n5==2 and n7==2 and sw ==0:
        goto(100,200)
        rt(135)
        pd()
        fd(430)
        i=10
        sw=1
    if i <10 : 
        n=numinput('','digite el numero donde quiere la O')
        if n ==1:
            goto(-160,130)
            write('O',font = ("arial",40,"bold"))
            n1=1
        if n ==2:
            goto(-60,130)
            write('O',font = ("arial",40,"bold"))
            n2=1
        if n ==3:
            goto(40,130)
            write('O',font = ("arial",40,"bold"))
            n3=1
        if n ==4:
            goto(-160,30)
            write('O',font = ("arial",40,"bold"))
            n4=1
        if n ==5:
            goto(-60,30)
            write('O',font = ("arial",40,"bold"))
            n5=1
        if n ==6:
            goto(40,30)
            write('O',font = ("arial",40,"bold"))
            n6=1
        if n ==7 :
            goto(-160,-70)
            write('O',font = ("arial",40,"bold"))
            n7=1
        if n ==8:
            goto(-60,-70)
            write('O',font = ("arial",40,"bold"))
            n8=1
        if n ==9:
            goto(40,-70)
            write('O',font = ("arial",40,"bold"))
            n9=1
        i = i +1   
    if n1==1 and n4==1 and n7==1 and sw ==0:
        goto(-150,200)
        rt(90)
        pd()
        fd(300)
        i=10
        sw=1
    if n1==1 and n2==1 and n3==1 and sw ==0:
        goto(-200,150)
        pd()
        fd(300)
        i=10
        sw=1
    if n1==1 and n5==1 and n9==1 and sw ==0:
        goto(-200,200)
        pd()
        rt(45)
        fd(4305)
        i =10
        sw=1
    if n4==1 and n5==1 and n6==1 and sw ==0:
        goto(-200,50)
        pd()
        fd(300)
        sw=1
        i=10
    if n7==1 and n8==1 and n9==1 and sw ==0:
        goto(-200,-50)
        pd()
        fd(300)
        i=10
        sw=1
    if n2==1 and n5==1 and n8==1 and sw ==0:
        goto(-50,200)
        rt(90)
        pd()
        fd(300)
        i=10
        sw=1
    if n3==1 and n6==1 and n9==1 and sw ==0:
        goto(50,200)
        rt(90)
        pd()
        fd(300)
        i=10
        sw=1
    if n3==1 and n5==1 and n7==1 and sw ==0:
        goto(100,200)
        rt(135)
        pd()
        fd(430)
        i=10
        sw=1

