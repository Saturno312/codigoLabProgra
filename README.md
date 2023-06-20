# codigoLabProgra
codigo de laboratorio de programacion
from tkinter import *
import webbrowser

tk= Tk()

new = 1
url = https://www.planteaenverde.es/blog/como-hacer-un-huerto-urbano-en-casa-3/
#Funcion que abre una pagina web 
def openweb():
    webbrowser.open(url,new=new)

#geometria de la ventana, si no de lo geometria, la ventana es del tamaño por defecto del boton
tk.geometry("660x660")
#creo boton cuyo comando es abrir la pagina web
Btn = Button(tk, text = "Nombre del boton",command=openweb)
#empaqueto el boton
Btn.pack()
#genero el loop para inicializar
tk.mainloop()




