# Amigo Oculto da Família

Página de sorteio de amigo oculto para mandar pelo WhatsApp. Cada pessoa recebe um link que mostra só quem ela tirou, e nem quem organiza vê o resultado.

## O que a página faz

- Cadastro do evento: nome, data, horário, local, valor do presente e um recado.
- Lista de participantes com WhatsApp e dica de presente.
- Quem não tem celular pode receber o link no celular de outra pessoa. Quem divide o mesmo número recebe um link só para todos.
- O sorteio forma uma corrente única sempre que dá, para ninguém trocar presente só entre si.
- Um botão por pessoa abre o WhatsApp com a mensagem pronta, e a página marca quem já recebeu.
- Convite para outra pessoa organizar junto.
- Lista de quem tirou quem para o organizador que não participa, escondida até ele pedir.
- Quem recebe o link vê só uma pergunta grande, "Você é Fulano?", com os botões Sim e Não. Quando o celular é de mais de uma pessoa, vai um link só, com o botão "Ver próxima pessoa". Depois do Sim, a página pergunta de novo "Tem certeza que é você?" antes de mostrar o nome.

## Como funciona

Tudo fica num único `index.html`, sem servidor. O resultado de cada pessoa vai embaralhado dentro do próprio link (depois do `#`). Isso basta para não estragar a surpresa, mas não é criptografia.

Quando a página roda como artefato do Claude, a lista do organizador fica salva na conta dele, então aparece igual no celular e no computador. Em qualquer outro lugar, ela fica salva no navegador.

## Usar em outro endereço

A página pode ser publicada em qualquer hospedagem estática, como o GitHub Pages. Depois de publicar, coloque o novo endereço em **Envie para cada um → Link da página**, para os links pessoais apontarem para lá.
