# Tradução do Ultima Underworld para pt-br

Projeto inacabado de tradução que inicou em 2007 (www.traducaoultima.net), foram envolvidas mais três pessoas que não recordo o nome.

Instruções para o arquivo strings-pt-br:
- Usar um editor de texto simples como o bloco de notas ou notepad++

- Algumas linhas são de identificação interna e não podem ser alteradas:
  "strings.pak: 122 string blocks.", "block: 0001; 512 strings.", etc...

- Os números antes das linhas não podem ser alterados
  
- Não pode quebrar a linha (Enter), deixas a formatação do jeito que está

- Manter alguns comandos como "\n"

- Caracteres inválidos: "[","]","#","@","$","<","*","%" e "X"(maiúsculo)
  tb não é suportado acentos gramaticas como "´","~","^" sozinhos, mas
  letras com acentos sim "ã","ç","ê", etc..

- Cuidado com espaços no final do texto,
  algumas falas utilizam outras linhas para complementar o texto
  ex: 
       70: You guess that it is currently 
       71: night
    no jogo ficaria: 
       You guess that it is currently night
    se o espaço não for respeitado pode dar erro:
       You guess that it is currentlynight

- Outros: Alguns substantivos estão juntos com os artigos:
  80: a_goblin, respeitar o underline "_" => um_goblin
  88: a_red lizardman&red lizardmen, respeitar o "_" e o "&"

- Alguns nomes de raças, itens e até o nome do jogo ficariam estranhos
  traduzir, então é melhor deixar com o nome original.

- Nunca alterar nada além do texto, nem criar novas linhas.
