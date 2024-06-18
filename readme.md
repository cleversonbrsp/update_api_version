# API Update Automation

Essa automação, escrita em Python utilizando o framework Flask, trata de um sistema para atualização de versão de uma API. O processo envolve o upload de um pacote de atualização, que é descompactado e utilizado para realizar backup de segurança, executar scripts de banco de dados, atualizar arquivos binários do site e verificar se a atualização foi bem-sucedida. A aplicação fornece uma interface web simples para gerenciar e monitorar essas operações.

## Pré-requisitos

1. **Sistema Operacional:** Deve ser executado em um sistema operacional compatível com Python e Flask, como Linux, macOS ou Windows.

2. **Python:** Certifique-se de ter o Python 3.x instalado. Você pode verificar isso executando `python3 --version` no terminal.

3. **Bibliotecas e Dependências:**
   - Flask: Para criar a aplicação web.
   - python-dotenv: Para carregar variáveis de ambiente de um arquivo `.env`.
   - subprocess: Para executar comandos do sistema.

   Instale as dependências com:
   ```sh
   pip install flask python-dotenv

![diagram](./img/diagram.png)
