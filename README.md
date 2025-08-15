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

Como Rodar o Projeto
Siga os passos abaixo para clonar o projeto e executá-lo em sua máquina local.

Clone o repositório:

Bash

git clone https://github.com/Luanalvesa/ConversorDeMoedas.git
Navegue até o diretório do projeto:

Bash

cd ConversorDeMoedas
Configurar a API Key (opcional, dependendo da sua implementação):

Se seu projeto usar uma API externa, obtenha sua chave.

Crie um arquivo de configuração (ex: config.properties) e adicione sua chave.

Execute o projeto com Maven:

Compile e gere o executável (JAR) do projeto:

Bash

mvn clean install
Execute o JAR gerado (o nome do arquivo pode variar):

Bash

java -jar target/conversor-de-moedas-1.0-SNAPSHOT.jar
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
