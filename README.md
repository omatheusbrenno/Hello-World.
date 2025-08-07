# 💻 Hello, World — com estilo!

Este projeto é um "Hello, World." diferente. Ele traz um toque de animação, tipografia bonita, e um estilo visual moderno, tudo em um só arquivo HTML.

🖤 Perfeito para quem está começando no front-end e quer já criar algo bonito, responsivo e animado!

---

## ✨ Demonstração

![Captura de Tela do Projeto](https://github.com/omatheusbrenno/hello-world.git)

> Você verá isso no seu navegador: um "Hello, World." com animação de digitação, seguido de uma frase motivacional.

---

## 📦 Como rodar no seu VSCode (em 3 passos)

1. **Clone este repositório:**

```bash
git clone https://github.com/omatheusbrenno/hello-world.git
```
2. **Abra a pasta no VSCode:**

```bash
cd hello-world
code .
```
3. **Execute com Live Server ou apenas pressione F5 (se tiver extensão Live Server instalada):**

> Se não tiver, clique com o botão direito no arquivo index.html → "Open with Live Server" ou apenas abra o arquivo no navegador.

## 🧠 O que esse projeto ensina?
- Como usar HTML5 moderno
- Como importar fontes do Google Fonts
- Como estilizar com CSS puro
- Como criar animações com keyframes
- Como fazer layout responsivo com media queries
- Como usar flexbox para centralizar tudo na tela

## 🧬 Explicação do código (aula didática 👇)

```bash
<!DOCTYPE html>
```
🧠 Diz ao navegador: “Isso é um HTML5”.

```bash
<html lang="pt-BR">
```
🌎 Define o idioma da página como português do Brasil.

```bash
<head>...</head>
```
🧠 Aqui ficam o título, as fontes, e os estilos.

```bash
  <link href="https://fonts.googleapis.com/css2?family=Inter:wght@300;600&display=swap" rel="stylesheet">
```
🎨 Importa a fonte Inter direto do Google Fonts.

```bash
body {
  background-color: #000;
  color: #fff;
  display: flex;
  justify-content: center;
  align-items: center;
}
```
🖤 Cria o fundo preto com texto branco, tudo centralizado na tela.

```bash
.typing {
  animation: typing 2s steps(15, end) forwards, blink 0.75s step-end infinite;
}
```
⌨️ Anima o texto como se estivesse sendo digitado, com um cursor piscando!

```bash
@keyframes typing { from { width: 0; } to { width: 15ch; } }
```
🚀 Faz a mágica acontecer: mostra o texto “letra por letra”.

## 📱 Responsivo também!
O site se adapta automaticamente a telas menores (como celular), diminuindo o tamanho da fonte.

## 🤝 Apoie este projeto
Se curtiu, ⭐ dá uma estrela aqui no GitHub
📲 Compartilha com alguém que está começando
🎥 Me segue no TikTok [@omatheuslana](https://www.instagram.com/omatheuslana) para mais projetos como esse!

## 📬 Fala comigo!
Quer sugerir algo ou aprender mais?

📧 Me chama no Instagram: [@omatheuslana](https://www.instagram.com/omatheuslana)
