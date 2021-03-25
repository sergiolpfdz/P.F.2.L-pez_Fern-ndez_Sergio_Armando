# P.F.2.L-pez_Fern-ndez_Sergio_Armando
ventana de tkinter import * #llamamos las librerias de tkinter.ttk import *

![image](https://user-images.githubusercontent.com/79875888/112424019-4e19ef80-8cf9-11eb-95a7-e0813ee081a6.png)

window = Tk () window.title ("programa") #con windos tk inicializamos o arrancamos un programa lbl = Label (window, text = "robot", font = ("Arial Bold", 50)) #tenemos un objeto etiqueta con sus atributos de palabras lbl.grid (column = 0, row = 0) #pocicionamiento de etiqueta

![image](https://user-images.githubusercontent.com/79875888/112424075-64c04680-8cf9-11eb-9aed-a1e0c7020dc0.png)

txt = Entrada (ventana, ancho = 0) #tenemos otros objetos de texto con su pocicionamiento txt.grid (columna = 0, fila = 1) txt.focus () #objeto focus

![image](https://user-images.githubusercontent.com/79875888/112424125-7c97ca80-8cf9-11eb-9cec-3cb9ba5dbf98.png)

def Cliked (): res = "inteligencia artificial" + txt.get () #metodo clik asignamos este evento y las secuencias que tendra al pulsar este objeto esque manda a llamar lbl.configure (text = res)
![image](https://user-images.githubusercontent.com/79875888/112424152-8de0d700-8cf9-11eb-97e4-338d6c8c8e97.png)

![image](https://user-images.githubusercontent.com/79875888/112424164-9507e500-8cf9-11eb-9258-9ebf5d35fdb6.png)

indow.geometry ("500x500") btn = Botón (ventana, texto = "clik", comando = Clik) ​​btn.grid (columna = 1, fila = 1) window.mainloop 

![image](https://user-images.githubusercontent.com/79875888/112424200-a2bd6a80-8cf9-11eb-969b-49780b11e2aa.png)
