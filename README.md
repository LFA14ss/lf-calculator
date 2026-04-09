# LF Calculator Desktop

Calculadora científica experimental para Windows, empacotada com Electron.

## Como gerar o .exe automaticamente

1. Suba este projeto no GitHub.
2. A Action "Build LF Calculator EXE" roda automaticamente.
3. Acesse a aba **Actions** no GitHub.
4. Clique no workflow mais recente.
5. Baixe o artefato **LF-Calculator-Windows** que contém o `LF-Calculator.exe`.

## Como rodar localmente

```bash
npm install
npm start
```

## Como compilar localmente

```bash
npm install
npm run dist
```

Saída em `dist/LF-Calculator.exe`.
