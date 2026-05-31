# 🌸 Calculadorinha pra minha namoradinha

Calculadora de notas de avaliações com pesos diferentes. Simples, rápida e fofa 💜

## ✨ Como funciona

1. **Configura** — nota máxima, arredondamento e tipo de peso
2. **Monta as questões** — adiciona Q1, Q2... com subquestões por quantidade
3. **Lança os acertos** — marca certo/errado ou quantas subquestões acertou
4. **Vê a nota** 🎉

## ⚖️ Tipos de peso

| Modo | Descrição |
|------|-----------|
| 🟰 Igual pra todas | Divide a nota máxima igualmente entre as questões |
| 🎚️ Peso por questão | Você define quantos pontos vale cada Q |
| 🔬 Peso por subquestão | Você define o peso de cada letra (a, b, c...) |

## 🚀 Publicar no GitHub Pages

### 1. Criar repositório

1. Acesse [github.com](https://github.com) → **New**
2. Nome: `calculadorinha` — deixe **Public**
3. **Não** marque "Add README"
4. Clique em **Create repository**

### 2. Enviar os arquivos

```bash
cd caminho/da/pasta/calculadorinha

git init
git add .
git commit -m "🌸 primeiro commit"
git remote add origin https://github.com/SEU_USUARIO/calculadorinha.git
git push -u origin main
```

> Se der erro, tente `git push -u origin master`

### 3. Ativar GitHub Pages

1. No repositório → **Settings** → **Pages**
2. Em **Branch**: selecione `main` e pasta `/ (root)`
3. Clique **Save**

Aguarde 1-2 minutos. Seu site vai estar em:

```
https://SEU_USUARIO.github.io/calculadorinha/
```

## 📂 Arquivos

```
calculadorinha/
├── index.html   ← tudo aqui (HTML + CSS + JS num arquivo só)
└── README.md    ← este arquivo
```

## 🛠️ Tecnologia

HTML + CSS + JavaScript puro. Sem dependências, funciona offline.
