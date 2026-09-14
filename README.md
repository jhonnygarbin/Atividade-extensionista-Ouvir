# Ouvir — Portal Web de Acessibilidade para Leitura Assistida

Projeto extensionista (CST em Análise e Desenvolvimento de Sistemas — UNINTER) focado em acessibilidade digital para pessoas com baixa visão e dificuldade de leitura.

## O que o site faz

- **Leitura em voz alta**: cole qualquer texto e ouça, com controle de velocidade, pausa e parada (via `Web Speech API` / `speechSynthesis`, nativa do navegador — sem custo, sem servidor).
- **Alto contraste**: alterna para um tema preto/amarelo de alto contraste.
- **Tamanho de fonte**: três níveis (A−, A, A+).
- **Fonte para leitura fácil**: alterna para uma tipografia mais legível.
- **Navegação por teclado**: todos os controles são acessíveis via `Tab`, com foco visível e um link "Pular para o conteúdo".

## Tecnologias

HTML5, CSS3 e JavaScript puro (sem frameworks, sem dependências externas). Um único arquivo (`index.html`), leve e fácil de hospedar.

## Como publicar no GitHub Pages

1. Crie um repositório novo no GitHub (por exemplo, `portal-acessibilidade`).
2. Suba o arquivo `index.html` (e este `README.md`) para a branch `main`.
3. No repositório, vá em **Settings → Pages**.
4. Em **Branch**, selecione `main` e a pasta `/root`, depois clique em **Save**.
5. Após alguns minutos, o GitHub mostrará o link público, algo como:
   `https://seu-usuario.github.io/portal-acessibilidade/`

## Como testar localmente

Basta abrir o arquivo `index.html` diretamente no navegador — não precisa de servidor.

Para testar a leitura em voz alta, use um navegador atualizado (Chrome, Edge ou Safari têm o melhor suporte a `speechSynthesis` em português).

## Compatibilidade testada

Recomenda-se testar em:
- Computador: Chrome, Edge, Firefox, Safari
- Celular: Chrome Android, Safari iOS

O suporte à Web Speech API varia entre navegadores; o site detecta a ausência de suporte e avisa o usuário nesse caso.
