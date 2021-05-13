
# Transportadora-API-REST<br>
Transportadora API REST em Spring Java <br>
Obs.: Consultar Branch [master] e seguir a estrutura das pastas.

<h1>ESTRUTURA</h1> <br>

- <h2>MODELS</h2><br>
    Atributos do objeto Pacote (Número do pacoteTipo, Categoria, Status).
      - Número do pacote: Aceito apenas com o match da regex 3 Letras e 4 Números, salvos em Uppercase.
      - Categoria: (Pacote, Caaixa, Envelope) Aceitando apenas valores predefinidos por Enum para melhor segurança dos dados.
      - Status (Recebido, Devolvido, Enviado, Cancelado) Aceitando apenas valores predefinidos por Enum.
      - Tipo (Simples, VIP)
- <h2>CONTROLLERS</h2><br>
    Contendo os endpoints e as chamadas para os services.
- <h2>SERVICES</h2><br>
    Contendo as regras de negócio, enum's, e condicionais de execução e chamamento dos metodos do Repository.
- <h2>REPOSITORY</h2><br>
    Contendo os metodos de interação direta com o banco de dados: Create Read Update Delete, além de procura por Categoria, Tipo ou Status.
    
DESENVOLVIMENTO<br>
    Desenvolvido em Framework Spring Java utilizando a IDE Netbeans 12.3, Modelo Java with Maven.
