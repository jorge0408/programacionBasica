# programacionBasica
## Tutorial de Python.

### Anaconda (distribuciÛn de Python).

#### øQuÈ es Anaconda?

Anaconda es un distribuciÛn libre y abierta de los lenguajes Python, utilizada en ciencia de datos, y aprendizaje autom·tico. Esto incluye procesamiento de grandes vol˙menes de informaciÛn, an·lisis predictivo y cÛmputos cientÌficos. Est· orientado a simplificar el despliegue y administraciÛn de los paquetes de software.

Las diferentes versiones de los paquetes se administran mediante el sistema de gestiÛn de paquetes conda, el cual lo hace bastante sencillo de instalar, correr, y actualizar software de ciencia de datos y aprendizaje autom·tico como ser Scikit-team, TensorFlow y SciPy.

La distribuciÛn Anaconda es utilizada por 6 millones de usuarios e incluye m·s de 250 paquetes de ciencia de datos v·lidos para Windows, Linux y MacOS.

#### InstalaciÛn de Anaconda.

Aunque instalar Python en una computadora es bastante sencillo, vamos a usar una distribuciÛn de Python gratuita llamada Anaconda. Aunque est· disponible sÛlo en inglÈs, esta distribuciÛn incluye multitud de utilidades que nos facilitar·n el trabajo y es ideal para empezar. Para instalarla, sÛlo tienes que descargar la versiÛn de Anaconda para tu sistema operativo desde su p·gina web.

Una vez instalado, sigue los siguientas pasos:

    1. Abrir el buscador de Windows.
    2. Abrir la carpeta "Anaconda(64-bits)".
    3. Hacer click en "Anaconda Prompt" o "Spider".

### Operadores

Tipo de datos b·sicos.

En python los tipos de datos b·sicos se dividen en, n˙meros, como pueden ser 3 (entero Û integer) 1.75, (punto flotante Û float) 7+5j (complejos Û complex).

Para poder conocer el tipo de dato de una variable susaremos la instrucciÛn "type()".

Otro tipo de dato basico en PYTHON son las cadenas de texto, por ejemplo, "Hola Mundo" (cadena de texto o string Û 'Hola Mundo' Û "Jenny's dog").

Como se puede notar a diferencia de muchos otros lenguajes en PYTHON no se declara el tipo de variable al crearla.

Para resumir en PYTHON se puede reprecentar n˙meros enteros, reales, y complejos. Los n˙meros enteros son aquellos n˙meros positÌvos o negatÌvos que no tienen desimales. En la mayor parte de las maquinas las variables enteras ("int") pueden almacrnar n˙meros de -2^31 a 2^31. En plataformas de 64 bites el rango es de -2^63 a 2^63.

Los n˙meros flotantes son los que tienen decimales. En PYTHON se expresan mediante el tipo "float" se puede representar n˙meros de -2^64 a 2^64.

Los n˙meros complejos son aquellos que tienen una parte imaginaria. Para definir una variable compleja se utiliza en termino "complex".

Operadores:

		suma                    r=3+2
		resta	                r=4-7
            (guiÛn) negaciÛn        r=-7
		multiplicaciÛn		r=2*6
		exponente		r=2**6
		divisiÛn		r=3.5/2
		divisiÛn entera		r=3.5//2
		modulo (residuo)	r=7%2

Un ejemplo de esto puede ser el siguiente:

    a=int(input('Incerta un numero '))   
    b=int(input('Incerta otro numero '))

    s=a+b   
    print('La suma es ' ,s)    
    r=b-a   
    print('La resta es ' ,r)    
    m=a*b   
    print('El producto es ' ,m)   
    d=a/b   
    print('El residuo es ' ,d)   
    dd=b/a
    print('El resultado es ' ,dd)    
    p=a**b   
    print('El resultado de "a" a la "b" es ' ,p)   
    import math    
    print('El logaritmo es ' ,math.log10(a))

### Sentencias condicionales.

Si un programa no fuera m·s que una lista de ordenes a ejecutar de forma secuencial, una por una, no tendria mucha utilidad. Las condicionales nos permiten comparar condicionales y hacer que nuestp programa se comparte de una forma u otra, que ejecute un fragmento de cÛdigo u otro, dependiendo de esas condiciones.

#### Condicional if.

La dorma m·s simple de una sentencia condicionales el "if" (del ingles "si") seguida de la condiciÛn a evaluar,(:) y en la siguiente linea in dentado, el codigo a ejutar en caso de que se cumpla sicha condiciÛn, como se muestra en el siguiente cÛdigo, que muestra el color de la casilla de un tablero de ajedres.

    casilla=str(input('escoje una casilla? :'))
    if casilla == ('a1'):
          print('casilla negra')
    elif casilla == ('a3'):
          print('casilla negra')
    elif casilla == ('a5'):
          print('casilla negra')
    elif casilla == ('a7'):
          print('casilla negra')
    elif casilla == ('b2'):
          print('casilla negra')
    elif casilla == ('b4'):
          print('casilla negra')
    elif casilla == ('b6'):
          print('casilla negra')
    elif casilla == ('b8'):
          print('casilla negra')
    elif casilla == ('c1'):
          print('casilla negra')
    elif casilla == ('c3'):
          print('casilla negra')
    elif casilla == ('c5'):
          print('casilla negra')
    elif casilla == ('c7'):
          print('casilla negra')
    elif casilla == ('d2'):
          print('casilla negra')
    elif casilla == ('d4'):
          print('casilla negra')
    elif casilla == ('d6'):
          print('casilla negra')
    elif casilla == ('d8'):
          print('casilla negra')
    elif casilla == ('e1'):
          print('casilla negra')
    elif casilla == ('e3'):
          print('casilla negra')
    elif casilla == ('e5'):
          print('casilla negra')
    elif casilla == ('e7'):
          print('casilla negra')
    elif casilla == ('f2'):
          print('casilla negra')
    elif casilla == ('f4'):
          print('casilla negra')
    elif casilla == ('f6'):
          print('casilla negra')
    elif casilla == ('f8'):
          print('casilla negra')
    elif casilla == ('g1'):
          print('casilla negra')
    elif casilla == ('g3'):
          print('casilla negra')
    elif casilla == ('g5'):
          print('casilla negra')
    elif casilla == ('g7'):
          print('casilla negra')
    elif casilla == ('h2'):
         print('casilla negra')
    elif casilla == ('h4'):
          print('casilla negra')
    elif casilla == ('h6'):
          print('casilla negra')
    elif casilla == ('h8'):
          print('casilla negra')
    else:
          print('casilla blanca')

O transformar algo tan com˙n, como la tu edad, a aÒos perros.

    humanos=float(input('Indique su edad humanos :'))
    perros1=((humanos-2)*(4))+21
    perros2=humanos*10.5
    if humanos > 2:
        print('la conversion de edad humanos a perros es de ',perros1)
    elif humanos < 0:
        print('favor de ingresar los datos de forma correcta')
    else: 
        print('la conversion de edad humanos a perros es de ',perros2)

### Bucle While.

Mientras que las condicionales permiten ejecutar distintos fragmentos de cÛdigo dependiendo de ciertas condiciones, los bucles permiten ejecutar un mismo fragmento de cÛdigo un cierto n˙mero de veces, mientras se cumpla una determinada acciÛn condiciÛn.

El bucle while(en espaÒol "mientras") ejecuta un fradmento de cÛdigo, mientras se cumpla la condiciÛn, tiene la siguiente estructura:

    llave='0123'
    pasword=''
    while True :
        pasword=input('inserte su pasword:')
        if pasword== llave:
            print('felicidades, entraste al sistema')
            break
        else:
            print('pasword incorrecto')
            print('intente de nuevo')    
    print('fin de programa')

### Ciclo For.

En pyhton "for" se utiliza como una forma genÈrica de interÈs sobre una secuencia, es decir, recorrer una secuencia.

    variable = secuencia  
    secuencia = ["uno", "dos", "tres"]  //estos son elementos
    for elemento in secuencia:
        print(elemento)                //4 esopacios 

Y los resultados ser·n:

    uno
    dos
    tres
    
El siclo "for" debe marcarse con un rango como se muestra de la siguiente manera:

    for temperatura in range(0,100,10):    //range es el rango y va el inicio, hasta
                                             donde quiero llegar y en este caso va de 10
    print(temperatura,'gC')                  en 10.

Un ejemplo del ciclo "for" puede ser el siguiente:

    for celcius in range(0,101,10):
        farenheit = (1.8*celcius)+32
        print(celcius,'gC','|',farenheit,'gF')

TambiÈn se puede hacer una lista de descuentos, como se muestra en el siguiente caso:

    for precio in range(4,201,5):
        precio=(precio+0.95)
        descuento = (precio*0.60)
        preciof=(precio-descuento)
        print(precio,'$','|',"{:.2f}".format(descuento),'|',"{:.2f}".format(preciof,'$'))

O incluso puedes hacer una tabla de multiplicar.

    print(' ',1,2,3,4,5,6,7,8,9,10)
    for a in range(1,11,1):
        x=a*1
        b=a*2
        c=a*3
        d=a*4
        e=a*5
        f=a*6
        g=a*7
        h=a*8
        i=a*9
        j=a*10
        print(x,a,b,c,d,e,f,g,h,i,j)

### Modulo Turlte 
Hay muchos mÛdulos en python que proveen caracterÌsticas poderosas que podemos usar en nuestros propios programas. Algunos de estos pueden enviar correos electrÛnicos y algunos de estos pueden extraer informaciÛn de paginas de Internet. Para el manejo de gr·ficos usaremos un modulo que permite crear figuras y patrones. El modulo que se usara permiten desarrollar nuestro pensamiento computacional.

      
    import turtle
    ventana=turtle.Screen()	//Crea una ventana en blanco			
    alex=turtle.Turtle()	//Crear un objeto de la clase turtle lo puedo llamar como yo quiera se llama "alex" y puede tener atributos
    alex.forward(50)	        //Avanza 50 unidades
    alex.left(90)		//gira a la izquierda 90∞
    alex.forward(30)	        //Avanza 30 unidades
    ventana.mainloop()	//Hasta que el usuario cierra la ventana el programa termina

Un ejemplo del modulo Turtle puede ser:

     import turtle
     ventana=turtle.Screen()
     alex=turtle.Turtle()
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     alex.left(90)
     alex.forward(100)
     ventana.mainloop()


Te aparecera una flecha, y no como tal una tortuga, pero si la quisieras ponlo de la siguiente manera:

    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor('red')
    ventana.title("Hola")

    alex=turtle.Turtle()
    alex.shape("turtle")
    alex.color("blue")
    alex.pensize(10)
    alex.forward(100)
    alex.left(120)
    alex.forward(100)
    ventana.mainloop() 

Aparte de poder figuras con el mismo codigo, y escojer el color de fondo o el color de la,  las tortugas:

    a=input('Escoje un color de los siguientes para la ventana: brown chocolate coral red pink purple blue green yellow black :  ')
    b=input('Escoje un color de los siguientes para la tortuga 1: brown chocolate coral red pink purple blue green yellow black :  ')
    c=input('Escoje un color de los siguientes para la tortuga 2: brown chocolate coral red pink purple blue green yellow black :  ')
    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor(a)
    ventana.title("Hola, Kary bebe")
    kary=turtle.Turtle()
    kary.shape("turtle")
    kary.color(b)
    kary.pensize(5)
    kary.forward(100)
    kary.left(120)
    kary.forward(100)
    kary.left(120)
    kary.forward(100)
    kary.left(120)
    kary.forward(100)
    kar=turtle.Turtle()
    kar.shape("turtle")
    kar.color(c)
    kar.pensize(5)
    kar.forward(100)
    kar.left(-120)
    kar.forward(100)
    kar.left(-120)
    kar.forward(100)
    kar.left(-120)
    kar.forward(100)
    ventana.mainloop() 
 
Puedes hacer tambiÈn puedes hacer cÌrculos con el Modulo Turtle, como este: 

    import turtle
    ventana=turtle.Screen()
    ventana.bgcolor("black")
    ventana.title("Hola")
    leo=turtle.Turtle()
    mike=turtle.Turtle()
    leo.shape("turtle")
    leo.color("green")
    leo.pensize(2)
    mike.shape("turtle")
    mike.color("red")
    mike.pensize(2)
    leo.speed(9)
    mike.speed(10)
    leo.penup()
    mike.penup()
    leo.setpos(0,-50)
    leo.pendown()
    leo.circle(50)
    mike.setpos(0,-100)
    mike.pendown()
    mike.circle(100)
    ventana.mainloop()

Incluso, con el Modulo Turtle, puedes poner imagenes. Pero solo imagenes que tengan extenciÛn ".gif", como se muestra en el siguiente caso:
(Nota: Tienes que guardar la imagen en la misna carpeta, donde estas guardando el programa)

    import turtle
    ventana=turtle.Screen()
    ventana.setup(1000, 500)
    ventana.tracer(0)
    ventana.addshape("mario.gif")
    mario=turtle.Turtle()
    mario.speed(0)
    mario.shape("mario.gif")
    mario.penup()
    mario.goto(-500, 0)
    while True:
        ventana.update()
        mario.forward(.5)

Y si quieres, incluso puedes hacer que la imagien rebote en el orde de la ventana.

    import turtle
    window= turtle.Screen()
    window.addshape("mario.gif")
    border= turtle.Turtle()
    border.speed(0)
    border.up()
    border.hideturtle()
    border.pensize(0)
    border.color('white')
    border.goto(500,500)
    border.down()
    border.goto(500,-500)
    border.goto(-500,-500)
    border.goto(-500,500)
    border.goto(500,500)
    camino=turtle.Turtle()
    camino.speed(0)
    camino.shape("mario.gif")
    camino.up()
    dx=1
    while True:
        x,y= camino.position()
        if x+dx>=500 or x+dx<=-500:
            dx=-dx
        camino.goto(x+dx,y)
    window.mainloop()

### FunciÛnes 

Una funciÛn es un fragmento de cÛdigo con un nombre asociado que realiza una serie de tareas y devuelve un valor. A dem·s de ayudarnos a programar y depurar dividiendo el programa en partes, las funciones tambiÈn permiten reutilizar cÛdigo.
     
	##definicion de una funcion
	def ladra():
	    print('guau, guau')
	##cuerpo principal del programa
	ladra()
Las Funciones ayudan al programador a dividir un problema en pequeÒas piezas que pueden ser re usadas. TambiÈn ayudan al programador a concentrarse en una pequeÒa parte del programa a la vez. Como resultado el escribir funciones es una parte importante del desarrollo del sofware. 

En nuestro caso debemos aprender a:

	1. Definir una funciÛn para usarla despuÈs.
	2. Pasar uno o m·s valores a una funciÛn.
	3. Desarrollar un c·lculo complejo en una funciÛn.
	4. Regresar uno o m·s resultados a una funciÛn.
	5. Llamar a una funciÛn que previamente hayamos definido.

Puede tambiÈn colocarce el Modulo Turtle con algunos de los ciclos, como se muestra este, con Ciclo For:

    import turtle
    def dibujar_cuadro(tur, d):
        for i in range(4):
            tur.forward(d)
            tur.left(90)
    ventana=turtle.Screen()
    ventana.bgcolor('green')
    ventana.title('Funciones')
    rafa = turtle.Turtle()
    dona = turtle.Turtle()
    dibujar_cuadro(rafa, 50)
    dibujar_cuadro(dona, 200)
    ventana.mainloop()

O tambiÈn se pueden cambiar el color de las lineas.

    import turtle
    def dibujar_cuadro(tur, d):
        for i in ['red','purple','blue','yellow']:
            tur.color(i)
            tur.forward(d)
            tur.left(90)
    ventana=turtle.Screen()
    ventana.bgcolor('green')
    ventana.title('Funciones')
    rafa = turtle.Turtle()
    dona = turtle.Turtle()
    dibujar_cuadro(rafa, 50)
    dibujar_cuadro(dona, 200)
    ventana.mainloop()

Incluso, con el mismo ciclo, puedes cambiar el angulo y el tamaÒo de las figuras.

    import turtle
    def dibujar_multiples_cuadro(tur, d):
        for i in ['red','purple','blue','yellow']:
            tur.color(i)
            tur.forward(d)
            tur.left(90)
    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('Funciones')
    alex = turtle.Turtle()
    alex.pensize(3)
    d=20
    for i in range(50):
        dibujar_multiples_cuadro(alex, d)
        d = d+10
        alex.forward(10)
        alex.right(18)
    ventana.mainloop()

O no solo que vallan creciendo, sino, que se queden en un mismo tamaÒo.

    import turtle

    def dibujar_cuadro_caracol(tur, d):
        for i in  ['red','blue','green','yellow']:
            tur.color(i)
            tur.forward(d)
            tur.left(90)

    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('funciones')

    alex=turtle.Turtle()
    alex.pensize(2)
    alex.speed(100)

    d=100

    for i in range(20):
        dibujar_cuadro_caracol(alex, d)
    
        alex.forward(10)
        alex.right(18)
        alex.setpos(0, 0)




    ventana.mainloop()

O hacer suceciones de un cuadrado, como se muestra en el siguiente programa:

    import turtle


    def dibujar_cuadro_seguir(tur, p):
        for i in range(4):
            tur.forward(20)
            tur.left(90)
    

    ventana=turtle.Screen()
    ventana.bgcolor('blue')
    ventana.title('funciones')

    omar=turtle.Turtle()
    omar.pensize(5)
    omar.speed(2)

    p=30

    for i in range(5):
        dibujar_cuadro_seguir(omar, 5)

        omar.penup()
        omar.setpos(p,0)
        omar.pendown()
        p=p+30

Y no solo que vallan hacia un lado, sino que, tambiÈn pueden hacerce cuadrados m·s grandes.

    import turtle

    def dibujar (tur,d):
        for i in range(4):
            tur.color('blue')
            tur.forward(d)
            tur.left(90)
     
     
    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('funciones')

    alex=turtle.Turtle()
    alex.pensize(3)
    alex.speed(20)

    m=-10

    for i in range(20,1591,20):
        dibujar(alex,i)
        alex.penup()
        alex.goto(m,m)
        alex.pendown()
        m=m-10

    ventana.mainloop()

O hacer incluso algo m·s extenzo y con un poco m·s de estÈtica:
 
    import turtle

    def cuadrado(tur, d):
        f=90
        for i in  range(500):
            tur.color('blue') 
            tur.forward(d)
            tur.left(f)
            d=d+5
            f=f+0.02
        
    ventana=turtle.Screen()
    ventana.bgcolor('black')
    ventana.title('funciones')

    d=15
    alex=turtle.Turtle()
    alex.speed(25)

    cuadrado(alex, d)

    ventana.mainloop()

### ProgramaciÛn Ambientada a Objetos.

Al principio del curso comentavamos que Python es un lenguaje multiparadigma en el que se podÌa trabajar con programaciÛn estructurada, como veniamos haciendo ahora o con programaciÛn orientada a objetos el cual es un paradigma de programaciÛn en el que los conceptos del mundo real relevantes para nuestro problema se modelan a travÈz de clases y objetos, y en el que nuestro programa consiste en una serie de interacciones entre objetos.

> OBJETOS:

> Un objetos es una entidad que agrupa un estado y una funcionalidad relacionada. El estado del objeto se define a travÈs de variables llamadas atributos, mientras que la funcionalidad de modela a travÈs de funciones a las que se les conoce con el nombre de M…TODOS DEL OBJETOS.

> **Diagrama UML sirve para definir un objeto y culales son su mÈtodos y sus atributos**

> Un ejemplo de objeto podrÌa ser un coche en el que tendriamos Atributos como: la marca, el numero de puertas, o el color.

> Y MÈtodos como: arrancar, parar.

> O bien cualquier otra combinaciÛn de Atributos y MÈtodos seg˙n lo que fuera relevante para nuestro programa.

> CLASES:

> Una clase no es m·s que una plantilla genÈrica de la cual insancia los objetos; es la plantilla que define que Atributos y MÈtodos tendr·n los objetos de esa clase.

En PYTHON las clases de definen Mediante la palabra clave "CLASS" seguido del nombre de la clase, seguido por dos puntos, y a continicaciÛn, inentado el cuerpo de la clase.

Por ejemplo:

    class Coche(object):
        def __init__(self,gasolina):
            self.gasolina = gasolina
        def arrancar(self):
            if self.gasolina > 0:
                print('Arranca')
            else:
                print('No Arranca')
        def conducir(self):
            if self.gasolina > 0:
                self.gasolina = self.gasolina - 1
                print('Quedan ', self.gasolina,' litros')
            else:
                print('No se mueve')
    vocho = Coche(5)
    tsuru = Coche(3)

    vocho.arrancar()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir()
    vocho.conducir() 

Pero no solo puedes poner algo en com˙n, como un carro, si no tambiÈn puedes hacer que el programa detecte si es o no, una figura, como por ejemplo un triangulo.

    class Triangulo(object):
        def __init__(self,angulo1,angulo2,angulo3):
            self.angulo1 = angulo1
            self.angulo2 = angulo2
            self.angulo3 = angulo3
        def ChecarAngulo(self):
            if self.angulo1+self.angulo2+self.angulo3 == 180:
                print('Es un triangulo')
            else:
                print('No es un triangulo')
    miTriangulo=Triangulo(90,30,60)
    miTriangulo.ChecarAngulo()

O incluso, puedes hacer que un programa continue una canciÛn en texto.

    class Cancion(object):
        def __init__(self,letra):
            self.letra = letra
        def cantame(self):
            print(self.letra)
    micumpleanos=Cancion(["...que cantaba el rey David," " hoy por ser dia de tu santo," " te las cantamos a ti."])
    micumpleanos.cantame()

![Pie de imagen](/imagenes/zadigOptions.png)
