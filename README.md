## Backend para Loja Virtual de Produtos Diversos
Este é o repositório do backend para uma loja virtual de produtos diversos, desenvolvido em Java com o framework Spring. O projeto utiliza o banco de dados H2 para testes por enquanto, e futuramente será implementado o banco PostgreSQL. 
Este projeto está sendo desenvolvido com o objetivo de estudo e revisão sobre o desenvolvimento de APIs REST a partir do java e spring.

### Funcionalidades:
- Cadastro, consulta, atualização e remoção de produtos.
- Gerenciamento de categorias de produtos.
- Autenticação de usuários.
- Histórico de pedidos.

### Arquitetura
#### O projeto segue o padrão de arquitetura em camadas, proporcionando uma separação clara de responsabilidades e facilitando a manutenção e evolução do código. As camadas incluem:

- Controller: Responsável por receber as requisições HTTP e encaminhá-las para o serviço apropriado.
- Service: Lógica de negócio da aplicação. Realiza operações sobre os dados recebidos dos controllers.
- Repository: Camada de acesso a dados. Responsável pela comunicação com o banco de dados.

### Diagrama de Classes (upload futuro)

### Próximos Passos
- Implementar integração com o banco de dados PostgreSQL para produção.
- Aprimorar os endpoints da API para melhorar a experiência do usuário.
- Adicionar testes automatizados para garantir a qualidade do código.
- Utilizar docker para o desenvolvimento local e deploy.

### Como Executar o Projeto Localmente
- Clone este repositório.
- Certifique-se de ter o Java JDK e o Maven instalados em sua máquina.
- Execute mvn spring-boot:run na raiz do projeto, ou rode com a IDE de sua preferência, para iniciar o servidor localmente.
- O backend estará disponível em http://localhost:8080.

Obrigado por conferir este projeto! Se você tiver alguma dúvida ou sugestão, sinta-se à vontade para entrar em contato.
