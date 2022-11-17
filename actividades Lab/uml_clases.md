@startuml
class Event{
    +starTime: DataTime
    +nombre: String
    +RegistrationClosed: boolean
    +execute()
}

class Hola{
    +perro:int
    -gato: String
}

class Foo{
    +estado: boolean
}

Hola <|--Foo : herencia

@endmul