# Ouvir — Portal Web de Acessibilidade para Leitura Assistida

Projeto extensionista (CST em Análise e Desenvolvimento de Sistemas — UNINTER) focado em acessibilidade digital para pessoas com baixa visão e dificuldade de leitura.

## O que o site faz

- **Leitura em voz alta**: cole qualquer texto e ouça, com controle de velocidade, pausa e parada (via `Web Speech API` / `speechSynthesis`, nativa do navegador — sem custo, sem servidor).
- **Alto contraste**: alterna para um tema preto/amarelo de alto contraste.
- **Tamanho de fonte**: três níveis (A−, A, A+).
- **Fonte para leitura fácil**: alterna para uma tipografia mais legível.
- **Navegação por teclado**: todos os controles são acessíveis via `Tab`, com foco visível e um link "Pular para o conteúdo".

## Tecnologias

HTML5, CSS3 e JavaScript puro (sem frameworks, sem dependências externas). 

## Compatibilidade testada

Recomenda-se testar em:
- Computador: Chrome, Edge, Firefox, Safari
- Celular: Chrome Android, Safari iOS

O suporte à Web Speech API varia entre navegadores; o site detecta a ausência de suporte e avisa o usuário nesse caso.
