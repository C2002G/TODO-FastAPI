DRY
    Você deve ter notado que a linha client = TestClient(app) está repetida na primeira linha dos dois testes que fizemos. Repetir código pode tornar o gerenciamento de testes mais complexo à medida que cresce, e é aqui que o princípio de "Não se repita" (DRY) 

    com isso tem a fitxture q é com conftest.py 