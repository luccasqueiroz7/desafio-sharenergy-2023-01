# Desafio para o processo seletivo SHARENERGY 2023/01

Link do vídeo de apresentação: https://youtu.be/muRseoa1V0E

# Instruções de configuração:

1. Abra o terminal e entre na pasta backend:

```bash
cd backend/
```

2. Instale todas as dependências:

```bash
yarn
```

3. Crie um arquivo .env, copiando o arquivo .env.example:

```bash
cp .env.example .env
```

4. Crie o seu banco de dados e complete o .env com as informações corretas, exemplo:

```bash
DB_HOST=localhost
DB_PASSWORD=123456
DB=desafio_sharenergy
DB_USER=luccas
SECRET_KEY=chave_secreta
```

5. Rode as migrações:

```bash
yarn typeorm migration:run -d src/data-source
```

6. Inicie o backend:

```bash
yarn dev
```

7. abra outro terminal e entre na pasta frontend:

```bash
cd frontend/
```

8. Instale todas as dependências:

```bash
yarn
```

9. Inicie o frontend:

```bash
yarn start
```

O frontend roda na porta 3000, enquanto o backend roda na porta 3001;

frontend: http://localhost:3000;

backend: http://localhost:3001;
