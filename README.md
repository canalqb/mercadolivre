# Sistema de Listagem de Produtos do CanalQb

Este sistema foi desenvolvido para listar todos os anúncios ativos do Mercado Livre, com o objetivo de manter os padrões da planilha de catálogo do Facebook. O sistema está disponível para que todos possam utilizá-lo.

Todos os arquivos são scripts Python (`.py`) convertidos em executáveis (`.exe`), para facilitar a utilização.

## Como Usar

1. **Download e Instalação:**
   - Faça o download dos arquivos `.exe` disponibilizados neste repositório.
   - Siga os passos iniciais de cada arquivo para configurá-los corretamente.

2. **Funcionamento do Sistema:**
   - O sistema foi projetado para ser fácil de usar. Após o download, basta seguir as instruções específicas de cada executável e aproveitar o funcionamento do sistema.

---

## Arquivo 1: `Categorias.exe`

Este arquivo não exige o uso de `APP_TOKEN`. Para utilizá-lo, siga os passos abaixo:

1. **Download:**
   - Faça o download do arquivo `Categorias.exe` e insira seu email para configurar o funcionamento.

2. **Configuração do Banco de Dados:**
   - Acesse o site [Vercel](https://vercel.com/), vá até a seção **Integrations** e crie um banco de dados **NEON**.
   - No painel de controle do **NEON**, vá para **Dashboard**, clique em **Connect** e copie a **Connection String**.
   - A **Connection String** deve ter a seguinte aparência:

     ```
     postgresql://neondb_owner:QWw4eos-pooler.us-east-1.aws.neon.tech/neondb?sslmode=require
     ```

3. **Inserção da Connection String:**
   - Insira a **Connection String** copiada no link do projeto para conectar ao banco de dados.

4. **Uso do Aplicativo:**
   - Após a configuração, basta rodar o aplicativo `Categorias.exe` e aproveitar suas funcionalidades.

---

## Considerações Finais

Este sistema foi desenvolvido com o intuito de facilitar a gestão de anúncios e a integração com o catálogo do Facebook. Caso tenha alguma dúvida ou queira contribuir com melhorias, sinta-se à vontade para abrir uma *issue* ou enviar um *pull request*.

Aproveite o sistema e boa sorte!
