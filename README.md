# Automação de Grupos Telegram

Este script automatiza a criação e configuração de grupos no Telegram.

## Requisitos

- Python 3.7 ou superior
- Conexão com internet
- Número de telefone registrado no Telegram

## Configuração

1. Instale as dependências:
```bash
pip install -r requirements.txt
```

2. Obtenha suas credenciais API:
   - Acesse https://my.telegram.org
   - Faça login com seu número
   - Crie um novo aplicativo
   - Copie o API_ID e API_HASH

3. Configure o arquivo `config.env`:
   - Substitua os valores com suas informações
   - Adicione os usernames dos bots
   - Especifique o caminho da foto do grupo
   - Adicione o username do novo proprietário

4. Adicione os nomes dos grupos em `groups.txt`:
   - Um nome por linha
   - Não use linhas vazias

## Uso

1. Execute o script:
```bash
python telegram_automation.py
```

2. Siga as instruções na tela
3. Na primeira execução, você precisará fazer login com seu número de telefone
4. O script criará e configurará os grupos automaticamente

## Funcionalidades

- Cria grupos
- Define foto do grupo
- Remove permissões dos usuários
- Adiciona bots como administradores
- Transfere propriedade do grupo
- Pausa entre operações para melhor controle