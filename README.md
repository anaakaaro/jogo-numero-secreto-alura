# Jogo do Número Secreto

Um jogo simples em JavaScript onde o jogador tenta adivinhar um número secreto. Projeto criado como exercício para praticar DOM, eventos e lógica básica em JavaScript.

## Índice
- **Descrição**: visão geral do projeto.
- **Como Jogar**: regras e instruções de uso.
- **Instalação**: como executar localmente.

## Descrição

O projeto contém uma página HTML com um pequeno jogo: o jogador escolhe números para tentar acertar o número secreto gerado pelo programa. É ideal para iniciantes em JavaScript e para praticar manipulação do DOM.

## Como Jogar

1. Abra o arquivo `index.html` (ou use um servidor local).
2. O jogo gera um número secreto entre 1 e 100 (ou conforme implementado no `app.js`).
3. Insira um palpite no campo disponível e clique em verificar/confirmar.
4. O jogo indicará se o palpite é maior, menor ou correto.
5. Ao acertar, o jogo pode permitir reiniciar para tentar novamente.

## Instalação / Executar localmente

Opções rápidas:

- Abrir diretamente no navegador:

	- Clique duas vezes em `index.html` na raiz do projeto.

- Servir via servidor HTTP (recomendado para evitar restrições de CORS ao abrir assets):

	- Se tiver Python instalado, abra um terminal na pasta do projeto e rode:

```powershell
python -m http.server 8000
```

	- Depois, abra `http://localhost:8000/` no navegador e acesse `index.html`.



