# API Update Automation

Essa automação, escrita em Python utilizando o framework Flask, trata de um sistema para atualização de versão de uma API. O processo envolve o upload de um pacote de atualização, que é descompactado e utilizado para realizar backup de segurança, executar scripts de banco de dados, atualizar arquivos binários do site e verificar se a atualização foi bem-sucedida. A aplicação fornece uma interface web simples para gerenciar e monitorar essas operações.

## Pré-requisitos

1. **Sistema Operacional:** Deve ser executado em um sistema operacional compatível com Python e Flask, como Linux, macOS ou Windows e com acesso ao banco.

2. **Python:** Certifique-se de ter o Python 3.x instalado. Você pode verificar isso executando `python3 --version` no terminal.

3. **Bibliotecas e Dependências:**
   - Flask: Para criar a aplicação web.
   - python-dotenv: Para carregar variáveis de ambiente de um arquivo `.env`.
   - subprocess: Para executar comandos do sistema.

## Instruções para Execução

1. **Clone o Repositório:**
   ```sh
   git clone <repository_url>
   cd <repository_directory>

2. **Instale as Dependências:**
   ```sh
   pip install -r requirements.txt

3. **Configure as Variáveis de Ambiente:**
Crie um arquivo .env com as variáveis necessárias.

4. **Inicie a Aplicação Flask:**
   ```sh
   python app.py
5. **Acesse a Aplicação:**
Abra o navegador e vá para http://127.0.0.1:5000 para acessar a interface web.
Seguindo esses passos, você estará pronto para utilizar a automação para a atualização da versão da API.

## Estrutura de pastas e arquivos do Projeto
   ```sh
   .
├── app.py                # Código principal da aplicação Flask
├── requirements.txt      # Lista de dependências Python
├── .env                  # Arquivo de variáveis de ambiente (não deve ser commitado)
├── scripts/              # Diretório contendo os scripts de backup, atualização de banco de dados e atualização de binários
│   ├── backup.sh
│   ├── execute_scripts.sh
│   └── update_binaries.sh
├── templates/            # Diretório contendo os templates HTML
│   └── index.html


![diagram](./img/diagram.png)
