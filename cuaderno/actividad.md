# reggistros en linux #

## Pwd 
(nos muestra en que carpeta estamos)
Home/sena

## Ls -l 
(nos muestra que carpeta tenemos)

## Cd desarrollo
(para aceder a la carpeta desarrollo)

## Ls -l 
(nos muestra que archivos entan en la carpeta desarrollo)

## Cd myapp
(para ingresar a la carpeta myapp)

## Code . 
(para entrar al editor de texto visual estudio code. entramos en inflectionscb => inflect.irregular "propietario","propietarios")

## Rails g scaffold propietario nombre:string, dirección string, teléfono integer
(para crear la base de dato por defecto y poniendole sus atributos)

##  Rake db: migrate
(encendemos la migracion)

 ## Rails c
 (crear nuevo objeto)

## a = persona.new
(hacemos la  creacion del objeto)

a.nombre: aleja
a.direccion: calle13
a.telefono:3014114221
### a.save
(con este comando guardamos los atributos)

b = persona.new
b.nombre: carlos
b.direccion: calle32
b.telefono:3097865431
b.save
 
c = persona.new
c.nombre: maria
c.direccion: calle8
c.telefono:3045670099
c.save 
 
d = persona.new
d.nombre: andres
d.direccion: calle9
d.telefono:3'856432211
d.save

e = persona.new
e.nombre: jpsefina
e.direccion: calle2
e.telefono:308741369
e.save 

e= persona.find(4)
e.destroy
(podemos borrar atributos)

d = pérsona.find(5)
d.nombre="juan"
d.save
(asi editamos los nombres agregados)

persona.all
(vemos los atributos que tenemos agregados)

### rails s
(para encender el servidor)

