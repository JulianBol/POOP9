@startuml
class Animal {
    -nombre: String
    -lugarOrigen: String
    -color: String
    +setNombre(String nombre)
    +setLugarOrigen(String lugarOrigen)
    +setColor(String color)
    +getNombre()
    +getLugarOrigen()
    +getColor()
    +sonido(String sound)
    +comer()

    }

class AnimalAcuatico{
    -numeroAletas:int
    +setNumeroAletas(int numeroAletas)
    +getNumeroAletas()
    +nadar()
}

class AnimalAereo{
    -numeroAlas:int
    +setNumeroAlas(int numeroAlas)
    +getNumeroAlas()
    +volar()
}

class AnimalTerrestre{
    -numeroPatas:int
    +setNumeroPatas(int numeroPatas)
    +getNumeroPatas()
    +correr()
}

class Ballena{
    -largo:int
    +setLargo(int largo)
    +getLargo()
    +pelearConPinocho()
}

class Pajaro{
    -tipoPico:String
    +setTipoPico(String TipoPico)
    +getTipoPico()
    +recolectarRamas()
}

class Perro{
    -colorCollar:String
    +setColorCollar(String ColorCollar)
    +getColorCollar()
    +hacerTrucos()
}

Animal <|--AnimalAereo : herencia

Animal <|--AnimalAcuatico : herencia

Animal <|--AnimalTerrestre : herencia

AnimalAcuatico <|--Ballena : herencia

AnimalAereo <|--Pajaro : herencia

AnimalTerrestre <|--Perro : herencia

@endmul