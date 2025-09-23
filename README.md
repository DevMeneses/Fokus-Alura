# Fokus
Aplicação simples de temporizador focada em produtividade, inspirada na técnica Pomodoro. O objetivo principal deste projeto é treinar manipulação de DOM (Document Object Model) com JavaScript puro, como parte de um curso da Alura.

## Objetivos de aprendizado
- Manipular o DOM para atualizar texto, classes, atributos e estado da interface
- Lidar com eventos de clique e alternância (toggle) de elementos
- Controlar temporizadores com `setInterval`/`clearInterval`
- Tocar/pausar áudios e controlar o volume via JavaScript
- Trocar contextos visuais (foco, descanso curto, descanso longo) pela árvore do DOM

## Funcionalidades
- Seleção de contexto: Foco, Descanso curto e Descanso longo
- Exibição do timer no elemento `#timer`
- Botão central de iniciar/pausar (`#start-pause`)
- Alternância de música ambiente com o checkbox `#alternar-musica`
- Mudança de cores e imagens conforme o contexto selecionado

> Observação: o arquivo `script.js` é onde a lógica de DOM/temporizador será implementada e evoluída ao longo do curso.

## Como executar localmente
1. Baixe ou clone este repositório
2. Abra o arquivo `index.html` diretamente no navegador
   - Opcional (recomendado): sirva a pasta com um servidor estático
     - VS Code + Live Server
     - Node: `npx serve`

## Estrutura do projeto
```
Fokus/
├── imagens/            # Ícones e imagens da interface
├── sons/               # Áudios (play, pause, beep, música ambiente)
├── index.html          # Estrutura principal da página
├── styles.css          # Estilos da aplicação
└── script.js           # Lógica de DOM e timer
```

## Tecnologias
- HTML5
- CSS3
- JavaScript (DOM API)

## Créditos
- Projeto educacional do curso da **Alura**
- Imagens: geradas por IA (Adobe Firefly), conforme indicado no rodapé

## Licença
Uso educacional. Ajuste conforme a sua necessidade.
