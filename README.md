Conversor de Moedas
Este é um aplicativo conversor de moeda simples, desenvolvido em Java, que permite converter valores entre diferentes moedas usando cotações atualizadas.

Funcionalidades
Conversão de moeda entre diversas moedas globais.

Interface de linha de comando ou gráfica (dependendo da implementação do projeto).

Obtenção de cotações em tempo real de uma API externa.

Tecnologias Utilizadas
Linguagem: Java

Gerenciador de Dependências: Maven (pelo arquivo pom.xml)

API de Cotação: Sugere-se o uso de uma API de cotação de moedas (como a ExchangeRate-API, Open Exchange Rates, ou similar) para obter dados em tempo real.

Pré-requisitos
Para rodar este projeto, você precisa ter o seguinte instalado:

Java Development Kit (JDK): Versão 8 ou superior.

Apache Maven: Versão 3.x.x ou superior.


Estrutura de Arquivos
A estrutura do projeto segue o padrão Maven:

.
├── .idea/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── com/
│   │           └── luanalvesa/
│   │               └── conversordemoedas/
│   │                   └── ...
├── .gitignore
└── pom.xml
