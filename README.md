![Logo UNAHUR](./assets/UNAHUR.png)



```
class Persona:
    def __init__(self, nombre, edad, carrera, facultad, gustos, foto_url):
        self.nombre = nombre
        self.edad = edad
        self.carrera = carrera
        self.facultad = facultad
        self.gustos = gustos
        self.foto_url = foto_url

    def presentarse(self):
        print(f"Hola, soy {self.nombre}, tengo {self.edad} años y estudio {self.carrera} en la {self.facultad}.")
        print(f"Éste soy yo, jeje \n {self.foto_url}")
        print("\nMis gustos:")
        for gusto in self.gustos:
            print(f"* {gusto.capitalize()}")
        print("\nTengo muchas expectativas para la materia y espero que todos tengamos una excelente cursada.")

if __name__ == "__main__":
    yo = Persona(nombre="Facundo Gré", edad=23, carrera="Licenciatura en Informática", facultad="Universidad de Hurlingham", gustos=["programación", "música", "fútbol", "fórmula 1", "lo' juegito' de compu eso' que juegan lo' pibe ahora, viste?", "juntarme con amigos", "comer"], foto_url="./assets/yo.jpg")
    yo.presentarse()
```
Output:

Hola, soy Facundo Gré, tengo 23 años y estudio Licenciatura en Informática en la Universidad de Hurlingham.

Éste soy yo, jeje 
 ![Yo](./assets/yo.jpg)

Mis gustos:
* Programación
* Música
* Fútbol
* Fórmula 1
* Lo' juegito' de compu eso' que juegan lo' pibe ahora, viste?
* Juntarme con amigos
* Comer

Tengo muchas expectativas para la materia y espero que todos tengamos una excelente cursada.
