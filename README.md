# Gerenciador de Produtos MVC

Este projeto implementa um simples sistema de gerenciamento de produtos usando o padrão de arquitetura MVC (Model-View-Controller) em Java.

## Descrição

O sistema consiste em três componentes principais:

- **Model (Modelo)**: Representado pela classe `Product`, que define a estrutura de dados de um produto, e pela classe `ProductRepository`, responsável por interagir com o banco de dados para salvar e recuperar produtos.

- **View (Visão)**: Representado pela classe `ProductView`, que é a interface gráfica do usuário. Nesta interface, os usuários podem adicionar novos produtos, visualizar todos os produtos existentes e receber feedback sobre as operações realizadas.

- **Controller (Controlador)**: Representado pela classe `ProductController`, que coordena a interação entre a visão e o modelo. O controlador configura os listeners de eventos nos componentes da interface do usuário e responde aos eventos executando as operações apropriadas no modelo.

## Como Usar

Para executar o projeto localmente, siga estas etapas:

1. Certifique-se de ter o Java Development Kit (JDK) instalado na sua máquina.
2. Clone este repositório para o seu ambiente local.
3. Abra o projeto em sua IDE Java preferida.
4. Compile e execute a classe `Main`.

Certifique-se de que você tem acesso a um banco de dados MariaDB (ou outro compatível) para armazenar os dados dos produtos. Certifique-se também de configurar corretamente as credenciais do banco de dados no arquivo `ProductRepository.java`.

## Contribuindo

Contribuições são bem-vindas! Se você encontrar um problema, tiver uma sugestão ou quiser melhorar este projeto de alguma forma, sinta-se à vontade para abrir uma issue ou enviar um pull request.

