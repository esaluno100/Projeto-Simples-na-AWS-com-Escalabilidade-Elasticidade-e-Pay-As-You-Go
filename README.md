# Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go
Aqui está um projeto simplificado que utiliza os princípios de escalabilidade, elasticidade e o modelo de pagamento pay-as-you-go, implementado com serviços básicos da AWS. 
O foco será criar uma aplicação web funcional e S3 para armazenamento estático.
Objetivo
Criar uma aplicação web escalável e econômica que permite:

# Projeto Simples na AWS com Escalabilidade, Elasticidade e Pay-As-You-Go 🚀

## Visão Geral
Este projeto demonstra a criação de uma aplicação simples utilizando serviços da AWS para garantir escalabilidade, elasticidade e o modelo de pagamento pay-as-you-go.

## Funcionalidades
- **Monitoramento de Estoque em Tempo Real**: Rastreamento dos níveis de estoque em múltiplas localizações.
- **Alertas Automáticos**: Notificações enviadas automaticamente quando os níveis de estoque atingem limites pré-definidos.
- **Escalabilidade**: Capacidade de aumentar ou diminuir os recursos automaticamente conforme a demanda.
- **Elasticidade**: Ajuste dinâmico dos recursos computacionais para manter a performance.
- **Pay-As-You-Go**: Pagamento pelos recursos utilizados, otimizando os custos.

## Pré-requisitos
- Conta na AWS
- Antes de começar, você precisará de:
- Git instalado no seu computador.
- AWS CLI configurada com suas credenciais.


## Configuração Inicial
Abra o terminal do prompt de comando do windows (um dos modos simples)
 **Clone o Repositório**:
   - Use o comando git clone seguido do URL do repositório:
   git clone https://github.com/seuusuario/Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go.git
   - observar que é seu usuário no github que vai inserir no código acima
   - Entre no diretório do projeto
   - Após clonar, navegue até o diretório do projeto:
     - cd Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go

## 🎯 Objetivos  Crie a Estrutura de Arquivos 🗂️    
- Dentro do diretório do projeto, crie a estrutura básica para os arquivos de código e documentação e testes:
- Crie os diretórios necessários:
- mkdir src docs tests
- touch README.md .gitignore

## Estrutura do projeto:
    - src/: Contém o código-fonte da aplicação.
    - docs/: Contém a documentação do projeto.
    - tests/: Contém os testes unitários e de integração.
    -  README.md: Este arquivo de documentação.
    - .gitignore: Arquivo para especificar quais arquivos ou diretórios o Git deve ignorar.

 ## ⚙️ Configuração da AWS 
   - Para hospedar a aplicação na AWS, você deve seguir os seguintes passos:

   - Configurar Credenciais da AWS 🛠️
   - Instale e configure o AWS CLI:
   - Se ainda não tem, instale o AWS CLI.[Instale pela Documentação da Aws] (https://aws.amazon.com/pt/cli/)
   - Configure o AWS CLI com suas credenciais usando o comando :
    aws configure

## ⚙️ Projeto Simples na AWS com Escalabilidade, Elasticidade e Pay-As-You-Go 🚀
   - Visão Geral
   - Este projeto demonstra a criação de uma aplicação simples que utiliza serviços da AWS para 
   - Garantir escalabilidade e elasticidade.
   - Aplicar o modelo de pagamento pay-as-you-go.
   - A aplicação foi configurada para monitoramento de estoque, com recursos que ajustam automaticamente a quantidade de recursos de acordo com a demanda.
________________________________________
## Funcionalidades 🛠️
 - Monitoramento de Estoque em Tempo Real. 
 - Acompanhamento dos níveis de estoque de diferentes produtos.
 - Alertas Automáticos: 
 -	Envio de notificações quando os níveis de estoque atingem valores críticos.
 -	Escalabilidade: 
 - Ajuste dinâmico dos recursos da aplicação conforme a demanda de tráfego.
 - Elasticidade: 
 - Capacidade de aumentar ou reduzir os recursos computacionais automaticamente para garantir a performance.
 - Pay-As-You-Go: 
 - Modelo de pagamento que só cobra pelos recursos utilizados, otimizando custos.
________________________________________
## Pré-requisitos 📋
- Antes de começar, você precisará de:
- Uma conta na AWS.
- Git instalado no seu computador.
- AWS CLI configurada com suas credenciais.
________________________________________
## Passo a Passo para Configuração do Projeto 📂
- Entre no diretório do projeto: 
- cd Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go
- Clone o Repositório 🧑‍💻
- Abra o terminal ou prompt de comando.
## 2.	Clone o repositório: 
- Use o comando git clone seguido do URL do repositório: 
- git clone https://github.com/seuusuario/Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go.git
## 3.	Navegue até o diretório do projeto: 
## 4.	cd Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go

## Configuração da AWS ⚙️
- Para hospedar a aplicação na AWS, você deve seguir os seguintes passos:
- Configurar Credenciais da AWS 🛠️
- Instale e configure o AWS CLI:
- Se ainda não tem, instale o AWS CLI.
- Configure o AWS CLI com suas credenciais usando o comando:
- aws configure

## Criar Bucket no S3 e Fazer Upload 📤

- Crie um bucket no AWS S3:
- Vá para o console AWS S3 e crie um novo bucket com um nome único.
- Faça upload do arquivo HTML:

## Faça o upload do arquivo index.html para o bucket.
 - Defina as permissões:
 - Certifique-se de que o arquivo seja acessível publicamente.
 - Configurar o Bucket para Hospedagem de Site Estático 🌐
 - Habilite a hospedagem de site estático:
 - No painel de configurações do S3, habilite a opção "Static website hosting".
 - Defina o arquivo index.html como o arquivo principal:
 - Configure index.html como o arquivo de índice da hospedagem.

# Meu Projeto

## Visão Geral
Este projeto demonstra a criação de uma aplicação simples que utiliza serviços da AWS para garantir escalabilidade, elasticidade e o modelo de pagamento pay-as-you-go.

---

## Instruções

- Após configurar o bucket e fazer o upload do arquivo HTML, siga estas etapas:
  - Envie os arquivos do seu site:
    - Clique em **Fazer Upload** no console do S3.
    - Adicione os arquivos necessários:
      - `index.html` (obrigatório)
      - Outros arquivos como `styles.css` ou imagens, se necessário.
    - Confirme e finalize o upload.

---

## Código HTML (index.html) 💻

---

## Imagem do Projeto
![Screenshot do Projeto](https://github.com/esaluno100/Projeto-Simples-na-AWS-com-Escalabilidade-Elasticidade-e-Pay-As-You-Go/blob/main/Pagina%20monitoramento%20Estoque.png)

---

Aqui está um exemplo do arquivo `index.html` que pode ser usado para monitoramento de estoque:

```html
<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Monitoramento de Estoque</title>
    <style>
        /* Estilização do corpo */
        body {
            font-family: Arial, sans-serif;
            background-color: #f4f4f4;
            margin: 0;
            padding: 0;
            display: flex;
            flex-direction: column;
            align-items: center;
            justify-content: center;
            height: 100vh;
        }

        /* Estilização do container principal */
        .container {
            background: #fff;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
            width: 80%;
            max-width: 500px;
        }

        /* Título */
        h1 {
            color: #333;
            text-align: center;
        }

        /* Itens do estoque */
        .stock-item {
            margin: 10px 0;
            padding: 10px;
            border: 1px solid #ddd;
            border-radius: 5px;
        }

        .stock-item p {
            margin: 5px 0;
            font-size: 16px;
        }

        /* Status do estoque */
        .status {
            padding: 10px;
            border-radius: 5px;
            color: #fff;
            font-weight: bold;
            text-align: center;
        }

        .low {
            background-color: #ff4d4d;
        }

        .high {
            background-color: #4caf50;
        }

        .medium {
            background-color: #ffc107;
            color: #000;
        }
    </style>
</head>
<body>
    <div class="container">
        <h1>Monitoramento de Estoque</h1>
        <div class="stock-item" id="itemA">
            <p>Produto A</p>
            <div class="status" id="statusA">Estoque Baixo</div>
        </div>
        <div class="stock-item" id="itemB">
            <p>Produto B</p>
            <div class="status" id="statusB">Estoque Médio</div>
        </div>
        <div class="stock-item" id="itemC">
            <p>Produto C</p>
            <div class="status" id="statusC">Estoque Suficiente</div>
        </div>
        <div>
            <h2>Atualizar Estoque</h2>
            <label for="produto">Selecione o Produto:</label>
            <select id="produto">
                <option value="A">Produto A</option>
                <option value="B">Produto B</option>
                <option value="C">Produto C</option>
            </select>
            <br><br>
            <label for="quantidade">Quantidade em Estoque:</label>
            <input type="number" id="quantidade" placeholder="Digite a quantidade">
            <br><br>
            <button onclick="atualizarEstoque()">Atualizar</button>
        </div>
    </div>

    <script>
        function atualizarEstoque() {
            // Obtém os valores do formulário
            const produto = document.getElementById("produto").value;
            const quantidade = parseInt(document.getElementById("quantidade").value);

            // Determina o status com base na quantidade
            let statusText = "";
            let statusClass = "";

            if (quantidade <= 10) {
                statusText = "Estoque Baixo";
                statusClass = "low";
            } else if (quantidade <= 50) {
                statusText = "Estoque Médio";
                statusClass = "medium";
            } else {
                statusText = "Estoque Suficiente";
                statusClass = "high";
            }

            // Atualiza o status no HTML
            const statusElement = document.getElementById(`status${produto}`);
            statusElement.textContent = statusText;
            statusElement.className = `status ${statusClass}`;
        }
    </script>
</body>
</html>

## Acessar o Site 🌍
- Após configurar o bucket e fazer o upload do arquivo HTML, Faça o Upload do Arquivo HTML
- Envie os arquivos do seu site

- Clique em Fazer Upload no console do S3.
- Adicione os arquivos necessários:
- index.html (obrigatório)
- Outros arquivos como styles.css ou imagens, se necessário.
- Confirme e finalize o upload.
- Você pode acessar seu site estático pela URL fornecida pelo S3. A URL será algo como

- http://nome-do-bucket.s3-website-us-east-1.amazonaws.com


##Faça o Upload do Arquivo HTML 📤
Envie os arquivos do seu site seguindo estas etapas:

## Clique em Fazer Upload no console do S3:

- Abra o console do AWS S3 e selecione o bucket que você criou.

- Clique no botão Fazer Upload.

- Adicione os arquivos necessários:

- index.html (obrigatório): Este é o arquivo principal da sua página.

- Outros arquivos como styles.css ou imagens, se necessário

- Adicione todos os arquivos adicionais que o seu site precisar para funcionar corretamente.

- Confirme e finalize o upload:

- Depois de adicionar todos os arquivos, clique em Next (Próximo) e siga as instruções para configurar permissões e propriedades.

- Confirme e finalize o processo de upload para garantir que todos os arquivos sejam carregados corretamente no bucket.
  
### Dicas de Solução de Problemas 🛠️

#### **403 Forbidden**
- **Verifique as permissões do bucket**: Certifique-se de que o bucket possui as permissões corretas para acesso público.
- **Política de acesso público**: Confirme se a política de acesso público do bucket está configurada
para permitir o acesso aos arquivos necessários.

#### **404 Not Found**
- **Nome do arquivo**: Verifique se o nome do arquivo no bucket corresponde exatamente ao nome definido como "Documento de índice".
- **Caminho correto**: Certifique-se de que o caminho do arquivo está correto e que não há erros de digitação.

#### **Atualizações**
- **Upload de nova versão**: Caso você altere os arquivos, faça o upload novamente
 para garantir que a versão mais recente seja carregada no bucket.
- **Cache do navegador**: Limpe o cache do navegador ou force uma atualização
para garantir que as alterações mais recentes sejam exibidas.4

#### [Visitem o site com uma apresentação deste projeto com um visual incrível]
 (https://projeto-simples-na-aws-00zg9rn.gamma.site/)

  ## **Contribuições**

Contribuições são bem-vindas! Sinta-se à vontade para enviar sugestões, abrir issues ou fazer um fork do repositório para melhorias.

 Como Contribuir
Faça um fork deste repositório.
Crie uma nova branch: git checkout -b minha-feature.
Faça suas alterações e commit: git commit -m 'Minha nova feature'.
Envie suas alterações: git push origin minha-feature.
Abra um pull request.

## **Licença**

Este projeto está licenciado sob a [MIT License](LICENSE).

## Observação Necessária: Permissões do Bucket

Verifique se as permissões do bucket permitem acesso público. A política básica para permitir acesso público é:

```json
{
    "Version": "2012-10-17",
    "Statement": [
        {
            "Effect": "Allow",
            "Principal": "*",
            "Action": "s3:GetObject",
            "Resource": "arn:aws:s3:::nome-do-bucket/*"
        }
    ]
}








         




