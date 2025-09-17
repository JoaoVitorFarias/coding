# Java

**Escreva uma vez, rode em qualquer lugar**

O código java (.java) é convertido em **.class** (bitcode), esse processo de compilação ocorre com o javac. A partir disso a JVM (Java Virtual Machine) interpreta os bitcodes.

- Objetos alocados dinamicamente, quando não possuem mais referência pra eles, serão desalocados pelo garbage collector
- Variáveis locais são desalocadas imediatamente  assim que seu escopo local sai de execução.

### Wrapper Classes
- São classes equivalentes aos tipos primitivos.
- Como: Interger, Boolean, Bigdecimal, String, Character, etc.
- Serve para fazer boxing e unboxing de forma natural
- Aceitam null e usufruem de recursos de OO

### List
- Inicia vazia, os elementos são alocados sob demanda
- Cada elemento ocupa um nó da lista
- Acesso sequencial dos elementos
- Não pode ter uma List de tipos primitivos, como: int, double, char...
- Interface: List
- Implementação: ArrayList, LinkedList
- Metodos da lista
    - Tamanho: size()
    - Remove com condição: removeIf(x -> !x)