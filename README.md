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

## Criando o primeiro repositório...

Iniciar um repositório vazio.

Demos um git init na pasta raiz do nosso projeto inicializar o controle de versões no projeto.

```bash
git init
```

Agora escrevemos a descrição das nossas alterações.

```bash
git commit -m "escreva a descrição do commit aqui"
```

## Ignorando arquivos com o git...

Às vezes não queremos adicionar em nosso repositório certos arquivo de configuração. Podemos, então, deixar de rastrea-los com o git simplemente adicionando um arquivo chamado <b>gitignore</b>. No exemplo paramos de ratrear o [ide-config](ide-config.txt).

```bash
git add .gitignore
```
