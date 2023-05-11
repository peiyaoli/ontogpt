
# Class: Environment




URI: [sample:Environment](http://w3id.org/ontogpt/environmental-sample/Environment)


[![img](https://yuml.me/diagram/nofunky;dir:TB/class/[NamedEntity],[Study]-%20environments%200..*>[Environment&#124;id(i):string;label(i):string%20%3F],[NamedEntity]^-[Environment],[Study])](https://yuml.me/diagram/nofunky;dir:TB/class/[NamedEntity],[Study]-%20environments%200..*>[Environment&#124;id(i):string;label(i):string%20%3F],[NamedEntity]^-[Environment],[Study])

## Identifier prefixes

 * ENVO

## Parents

 *  is_a: [NamedEntity](NamedEntity.md)

## Referenced by Class

 *  **None** *[➞environments](study__environments.md)*  <sub>0..\*</sub>  **[Environment](Environment.md)**

## Attributes


### Inherited from NamedEntity:

 * [➞id](namedEntity__id.md)  <sub>1..1</sub>
     * Description: A unique identifier for the named entity
     * Range: [String](types/String.md)
 * [➞label](namedEntity__label.md)  <sub>0..1</sub>
     * Description: The label (name) of the named thing
     * Range: [String](types/String.md)