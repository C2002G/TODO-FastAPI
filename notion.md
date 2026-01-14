DRY
    Você deve ter notado que a linha client = TestClient(app) está repetida na primeira linha dos dois testes que fizemos. Repetir código pode tornar o gerenciamento de testes mais complexo à medida que cresce, e é aqui que o princípio de "Não se repita" (DRY) 

    com isso tem a fitxture q é com conftest.py 
        conftest.py é um arquivo especial reconhecido pelo pytest que permite definir fixtures que podem ser reutilizadas em diferentes módulos de teste em um projeto. É uma forma de centralizar recursos comuns de teste.

Para os testes
    task lint

    task format

    task test