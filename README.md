# Bubbles Macro Extension Tool

Editor de macros do **Corsair iCUE** que roda no navegador: cada macro é uma bolha.

**Abrir a ferramenta: https://carlucio7.github.io/bubbles-macro-tool/**

Não precisa instalar nada nem criar conta. Tudo acontece na sua máquina: o perfil
que você abre não é enviado a lugar nenhum.

## O que ela faz

- Abre o perfil exportado do iCUE (`.cueprofile`) e mostra as macros como bolhas.
- **Criar com bolhas**: monte uma macro nova clicando ou arrastando outras macros e
  modelos prontos (espera, tecla + clique, ir até um ponto, digitar texto...).
- **Palco**: arraste para mudar a ordem, solte uma bolha sobre outra para formar um
  conjunto, gire a roda do mouse para repetir N vezes, dê nome às partes da macro.
- **Repetições de verdade**: "repetir 54 vezes" fica escrito uma vez só e vira os
  54 passos na hora de salvar - o iCUE sozinho só repete a macro inteira.
- **Prévia animada**: um projétil percorre a macro no tempo real dela e mostra as
  teclas, cliques e movimentos que seriam enviados. Nada é apertado de verdade.
- **Pontos da tela**: capture a tela por um botão (ou cole um Print Screen) e clique
  nos pontos na imagem.
- **Lista de passos completa**: arrastar, copiar e colar, ajustar muitas esperas de
  uma vez, agrupar e desagrupar.
- Salva uma cópia editada do perfil; o arquivo que você exportou nunca é alterado.
- Português e inglês, tema claro e escuro.

## Como usar

1. No iCUE, exporte o perfil: três pontinhos do perfil → **Exportar**, com
   **Atribuições de Tecla** e **Ações de tecla** ligadas.
2. Abra a ferramenta e clique em **Abrir perfil…** (ou solte o arquivo na página).
3. Edite e clique em **Salvar**.
4. No iCUE, importe o arquivo salvo: três pontinhos de um perfil → **Editar** →
   **Importar / Exportar perfis** → **Importar**.
   O iCUE sempre cria um perfil novo ao importar.

A própria página tem os dois tutoriais, com desenhos ("Como exportar…" e
"Como importar…").

## Limites conhecidos

- Movimentos absolutos do mouse no iCUE só alcançam o monitor principal.
- Uma página não consegue gravar teclado e mouse nem ler a posição do mouse fora
  dela: os pontos são marcados numa imagem da tela.
- A captura de tela por botão depende do navegador (Chrome, Edge, Firefox no
  computador).

## Sobre

Projeto pessoal, gratuito e de código aberto (licença MIT). O arquivo `index.html`
contém a ferramenta inteira, com o código legível.

Não é um produto da Corsair nem tem ligação com ela. "Corsair" e "iCUE" são marcas
dos seus donos. Use por sua conta: confira as macros no iCUE depois de importar.

---

**English.** A browser editor for Corsair iCUE macros: open an exported
`.cueprofile`, build and edit macros as draggable bubbles, watch an animated
preview and save an edited copy. Nothing is uploaded - it all runs in your browser.
Open it at https://carlucio7.github.io/bubbles-macro-tool/ (the page has an
English option in its "⋯" menu). Free and open source (MIT). Not affiliated with
Corsair.
