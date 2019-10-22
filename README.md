# Turing-Machine
Máquina de Turing Universal. Recebe como entrada uma outra máquina de Turing e uma palavra de entrada

Building Blocks
LER http://www.jflap.org/tutorial/turing/buildingblocks/buildingblocks.htm
Usado para criação de grandes Máquinas de Turing


Casos de Teste

- (1)Entrada: String -> Máquina de Turing e palavra aceita pela MT de entrada
            - Diferentes MT e diferentes palavras aceitas
- (2)Entrada: String-> Máquina de Turing e palavra rejeitada pela MT de entrada
            - Diferentes MT e diferentes palavras rejeitadas
- (3)Entrada: String-> Não representa uma máquina de Turing e palavra que seria aceita por uma
            - Diferentes Strings que não representam uma MT 
            - Mesmas palavras do teste (1)
- (4)Entrada: String-> Não representa uma máquina de Turing e palavra que não seria aceita por uma
            - String do teste (3)
            - Mesmas palavras do teste(2)
