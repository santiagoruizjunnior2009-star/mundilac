**import tkinter as tk

def saludar():
    nombre = entrada.get()
    etiqueta_resultado.config(text=f"Hola, {nombre}")

# Crear ventana
ventana = tk.Tk()
ventana.title("Mi primera interfaz")
ventana.geometry("300x200")

# Widgets
etiqueta = tk.Label(ventana, text="Escribe tu nombre:")
etiqueta.pack()

entrada = tk.Entry(ventana)
entrada.pack()

boton = tk.Button(ventana, text="Saludar", command=saludar)
boton.pack()

etiqueta_resultado = tk.Label(ventana, text="")
etiqueta_resultado.pack()

# Ejecutar
ventana.mainloop()
**
