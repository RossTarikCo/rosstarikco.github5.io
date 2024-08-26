```mermaid
    classDiagram

    class Animal{
        eat()
        numLegs int 
        class String
        color String 
        hasTail boolean
        reproduce()
        die()
    }

    class Zebra{
        trot()
        gallup()
        numStripes byte
    }

    Animal <|-- Zebra

    class MountainZebra{
        mountainRange
        hillClimb()
    }

    Animal <|-- MountainZebra
