## Necesidad

En su labor como desarrollador de software la empresa TuSaco lo ha contactado con el fin de implementar un sistema de inventario que ayude al personal del almacen. el inventario de la tienda se compone de diferentes tipos de sacos, cada uno con una referencia o ID, una descripcion un precio y una cantidad disponible.

### Historia de Usuario:
Yo como administrador del almacen de la empresa TuSaco, requiero un Software que me permita llevar un control mas organizado del inventario del almacen.

#### Escenarios
###### Escenario 1:
Ingreso correctamente la referencia o el id del saco
Ingreso correctamente la descripcion del saco
Ingreso correctamente el precio del saco
Ingreso correctamente la cantidad

selecciono la opcion para ver cuantos sacos hay de una referencia

debo poder guardar la informacion del saco como:
- referencia
- descripcion
- precio
- cantidad
se debe poder ver la cantidad de sacos que hay en el inventario

### Caso de uso:
![Caso de uso](https://github.com/emancerar/TiendaSacos.io/blob/6b087e5a6d089b7836c1f8dbbd508126832890f3/Casos%20de%20uso.png)


### Diagrama de Flujo:



### Seudocódigo:

Inicio
	Real: IdSaco, Precio, Cantidad
	Caracteres: Descri[50]
	Entero: Opc
	Repetir
		Imprimir: ‘Seleccione una opcion:’
		Imprimir: ‘1. Ver Inventario’
		Imprimir: ‘2. Ingresar Saco’
		Asignar: Opc
		Si Opc=1 Entonces
			Los Sacos en almacen son:
			IdSaco,  Descri[50], 
			Precio, Cantidad
		SiNo
			Si Opc=2 Entonces
				Imprimir: ‘Ingrese el ID del saco:’
				Asignar: Id
				Imprimir: ‘Ingrese la descripcion del saco:’
				Asignar: Descri
				Imprimir: ‘Ingrese el precio del saco:’
				Asignar: Precio
				Imprimir: ‘Ingrese la cantidad sacos:’
				Asignar: Cantidad
			Fin Si
		Fin Si
	Hasta Que Opc=1 O Opc=2
Fin

