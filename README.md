<h1>Comandos GIT</h1>

## Configurando o git...

### Locais

Usamos o comando <code>--local</code> para definir o nome e o email do responsável pelas alterações no repositório.

```bash
git config --local user.name "nome da pessoa aqui"
```

```bash
git config --local user.email "email da pessoa aqui"
```

### Globais

Com o comando <code>--global</code> você pode setar seu nome e email para todos os repositórios que você criar na sua máquina.

```bash
git config --global user.name "nome da pessoa aqui"
```

```bash
git config --global user.email "email da pessoa aqui"
```

### Criando o primeiro repositório...

Iniciar um repositório vazio

```bash
git init
```

Demos um git init na pasta raiz do nosso projeto para começar a inicializar o controle de versões no projeto.

```bash
git commit -m "escreva a descrição do commit aqui"
```
