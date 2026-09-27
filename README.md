
# Laboratório 01 — Programação Orientada aos Objetos

## Identificação

Aluno: Volodymyr Lapshyn  
Unidade Curricular: Programação Orientada aos Objetos  
Ambiente: macOS  
Linguagem: Java  
IDE: Visual Studio Code

## Objetivo

Configurar um ambiente de desenvolvimento Java, criar e executar programas, utilizar o debugger do VS Code e aplicar os comandos essenciais do Git e GitHub.

## Estrutura do projeto

```text
lab01/
├── .vscode/
│   ├── launch.json
│   └── tasks.json
├── docs/
├── out/
├── src/
│   ├── main/
│   │   └── java/
│   │       └── escnaval/
│   │           └── exemplo/
│   │               ├── HelloWorld.java
│   │               └── ArgsEcho.java
│   └── test/
├── .gitignore
└── README.md
```

## Compilação

No terminal do VS Code:

```bash
javac -d out $(find src/main/java -name "*.java")
```

## Execução

### HelloWorld

```bash
java -cp out escnaval.exemplo.HelloWorld
```

### ArgsEcho

```bash
java -cp out escnaval.exemplo.ArgsEcho ola mundo 123
```

## Depuração

A depuração foi realizada através do VS Code, utilizando:

- Breakpoints;
- Inspeção de variáveis;
- Watch;
- Call Stack;
- Step Over e Step Into.

## Checklist de entrega

- [x] HelloWorld imprime a mensagem no terminal e no VS Code.
- [x] ArgsEcho imprime os argumentos recebidos.
- [x] .gitignore exclui builds, caches e ficheiros da IDE.
- [x] README.md explica como compilar e executar os programas.
- [x] Repositório no GitHub com commits claros por objetivo.
- [x] Screenshot da depuração na pasta docs/ (opcional).

## Controlo de versões

O projeto foi desenvolvido utilizando Git e sincronizado com um repositório remoto no GitHub.

