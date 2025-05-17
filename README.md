# analog.IA-projeto
Analog.IA é um sistema de múltiplos agentes projetado para explicar conceitos de forma clara e memorável através de cards minimalistas com analogias visuais.

O sistema funciona da seguinte maneira:

Agente_buscador: Este agente recebe uma pergunta sobre um conceito e busca informações confiáveis e detalhadas sobre ele na internet, priorizando fontes como enciclopédias online e sites educacionais renomados. A saída é um resumo detalhado e bem referenciado do conceito.

Agente_Resumo_Analogia: Este agente recebe a informação detalhada do conceito e realiza duas tarefas principais: cria um resumo conciso e em linguagem acessível, adequado para um card, e desenvolve uma analogia visual simples e memorável para explicar o conceito de forma intuitiva. A saída são o resumo e a analogia visual (descrita textualmente) separados.

Agente_Criador_Card: Este agente recebe a pergunta original, o resumo do conceito e a analogia visual. Sua função é criar o conteúdo textual para o card (título conciso e texto explicativo curto utilizando a analogia) e descrever a ilustração minimalista que representará a analogia visual, especificando os elementos simbólicos e o estilo de linhas finas.

Agente_Criador_Prompt_Imagem: Este agente recebe a pergunta original, o resumo com a analogia visual e o conteúdo do card (título, texto e descrição da ilustração). Sua tarefa é gerar um prompt de texto bem formatado para uma IA de geração de imagens. Este prompt instrui a IA a criar uma ilustração minimalista no formato vertical de card, utilizando linhas finas e a analogia visual como foco central, complementando o título e o texto do card.

O objetivo do Analog.IA é transformar a explicação de conceitos complexos em cards visuais simples, diretos e eficazes, facilitando o aprendizado através de analogias representadas de forma minimalista.
