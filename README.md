<!DOCTYPE html>
<html lang="pt-BR">
<head>
    <meta charset="UTF-8">
    <title>README - Gerador de Paletas de Cores</title>
</head>
<body>

<div align="center">
  <h1 style="font-size: 3em; font-weight: bold;">🎨 Gerador de Paletas de Cores 🎨</h1>
  <p>
    Uma aplicação web simples e elegante para explorar, visualizar e copiar paletas de cores temáticas.
  </p>
  <p>
    Criado para designers, desenvolvedores e entusiastas de cores que precisam de inspiração rápida e funcional.
  </p>
</div>

<br>

---

## 🌟 Visão Geral do Projeto

Este projeto é uma página HTML interativa que apresenta uma coleção curada de 22 paletas de cores. Cada paleta é exibida visualmente, e com um único clique, os códigos hexadecimais correspondentes podem ser copiados para a área de transferência, prontos para serem usados em qualquer ferramenta de design ou desenvolvimento.

<br>

---

## ✨ Funcionalidades

<ul>
  <li><strong>Visualização Imediata:</strong> Veja como as cores de cada paleta se combinam.</li>
  <li><strong>Cópia Fácil:</strong> Botão "Copiar Cores" que prepara um prompt formatado (ex: <code>Utilize a seguinte paleta de cores: #BCDFB9, #C87F8B, ...</code>) para uso imediato.</li>
  <li><strong>Design Responsivo:</strong> Interface limpa e funcional em qualquer dispositivo, construída com Tailwind CSS.</li>
  <li><strong>Grande Variedade de Temas:</strong> Inclui 22 paletas organizadas por temas criativos, como:
    <ul>
      <li>Retrô (Anos 1950 e 1970)</li>
      <li>Pós-apocalíptico</li>
      <li>Inspiração Asiática</li>
      <li>Cinematográfico (O Iluminado)</li>
      <li>Tons Pastéis e muito mais!</li>
    </ul>
  </li>
  <li><strong>Código Leve:</strong> Feito com HTML, CSS (via Tailwind CDN) e JavaScript puro, sem dependências complexas.</li>
</ul>

---

## 🚀 Como Usar

1.  **Abra o arquivo `index.html`** em qualquer navegador web moderno.
2.  **Navegue pelas paletas** para encontrar a inspiração que procura.
3.  **Clique no botão "Copiar Cores"** da paleta desejada.
4.  **Cole o texto copiado** na sua ferramenta de IA, software de design (Figma, Photoshop) ou no seu editor de código (VS Code).

---

## 🎨 Exemplo de Paleta no App

<div style="border: 1px solid #ddd; border-radius: 12px; padding: 20px; background-color: #ffffff; max-width: 600px; margin: auto; font-family: sans-serif;">
    <h3 style="font-size: 1.5em; margin-top: 0; margin-bottom: 15px; color: #222;">Tema: Filme "O Iluminado"</h3>
    <h4 style="font-size: 1.2em; margin-top: 0; margin-bottom: 15px; color: #444;">Tapete do Overlook</h4>
    <div style="display: flex; height: 80px; border-radius: 8px; overflow: hidden; margin-bottom: 15px;">
        <div style="background-color: #9B2305; flex-grow: 1;"></div>
        <div style="background-color: #CF6F0A; flex-grow: 1;"></div>
        <div style="background-color: #581F08; flex-grow: 1;"></div>
        <div style="background-color: #000000; flex-grow: 1;"></div>
        <div style="background-color: #F5F5F5; flex-grow: 1;"></div>
    </div>
    <button style="padding: 10px 18px; border: none; background-color: #007bff; color: white; border-radius: 6px; cursor: pointer; font-size: 1em;">
        Copiar Cores
    </button>
</div>

<br>

---

## 🛠️ Tecnologias Utilizadas

- **HTML5:** Para a estrutura da página.
- **Tailwind CSS:** Para estilização rápida e responsiva.
- **JavaScript:** Para a funcionalidade de cópia para a área de transferência.
- **Google Fonts:** Para a tipografia (família de fontes 'Inter').

</body>
</html>
