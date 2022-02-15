<h1>Comandos GIT</h1>

[Configuração](#configurando-o-git) ||
[Iniciando repositório](#criando-o-primeiro-repositório) ||
[Vendo as alterações](#vendo-alterações-do-projeto) ||
[Ignorando arquivos](#ignorando-arquivos-com-o-git)

<br>

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

Com o comando <code>--global</code> você pode setar seu nome e email para todos os repositórios que você criar na sua máquina a partir daquele momento.

```bash
git config --global user.name "nome da pessoa aqui"
```

```bash
git config --global user.email "email da pessoa aqui"
```

<br>

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

<br>

## Vendo alterações do projeto

Para vizualizar as alterações que fez no projeto, usa-se o flag <b>log</b>.

Ver todos os commits

```bash
git log
```

Ver os commits ocupando uma linhas

```bash
git log --oneline
```

Ver mais informações

```bash
git log -p
```

## Ignorando arquivos com o git...

Às vezes não queremos adicionar em nosso repositório certos arquivo de configuração. Podemos, então, deixar de rastrea-los com o git simplemente adicionando um arquivo chamado <b>.gitignore</b>. No exemplo paramos de ratrear o <b>ide-config</b>.

```bash
git add .gitignore
```
