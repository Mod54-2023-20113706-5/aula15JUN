# Atividade M.A.P.A


A criação de um branch é uma prática fundamental no controle de versão de um repositório, conforme representado no diagrama. Inicialmente, o repositório possui um branch principal, geralmente denominado "main", considerado a versão definitiva do código. Ao criar um novo branch, como exemplificado no diagrama pelo "feature", os desenvolvedores podem explorar e implementar novas funcionalidades sem impactar diretamente o código principal.

A sequência de atividades começa com a criação do branch a partir do "main", criando uma cópia independente para o desenvolvimento paralelo. Durante o processo, alterações são feitas e registradas no branch "feature". Posteriormente, essas modificações passam por fases como "Fazer commit de alterações", onde são registradas no histórico do branch. Em seguida, o desenvolvedor envia uma "solicitação de pull", propondo a fusão das alterações ao branch principal.

A fase final envolve a discussão das alterações propostas, garantindo uma revisão adequada antes da fusão. Uma vez aprovado, o branch "feature" é mesclado de volta ao "main", consolidando as alterações e mantendo a integridade do código principal. Essa sequência proporciona um ambiente de desenvolvimento flexível e controlado.

Esquematização de um branch:

Identificação do Branch Principal (Main): Inicialmente, o desenvolvedor identifica o branch principal, geralmente chamado de "main" ou "master", que representa a versão estável do código.

Criação do Novo Branch (Feature, por exemplo): Um novo branch é criado a partir do branch principal. Esse novo branch, muitas vezes chamado de "feature" para indicar uma nova funcionalidade, é uma linha de desenvolvimento independente.

Desenvolvimento Isolado: As alterações e adições de código são realizadas no novo branch ("feature"), permitindo que os desenvolvedores trabalhem em novas funcionalidades ou correções sem afetar diretamente o código do branch principal.

Commits e Registro de Alterações: Durante o desenvolvimento no novo branch, os desenvolvedores fazem commits para registrar as alterações realizadas. Cada commit representa uma versão específica do código.

Solicitação de Pull (Pull Request): Após concluir o desenvolvimento no novo branch, o desenvolvedor envia uma solicitação de pull, indicando que deseja mesclar as alterações de seu branch com o branch principal.

Revisão e Discussão: Outros membros da equipe revisam as alterações propostas na solicitação de pull. Pode haver discussões, correções e feedback antes de prosseguir.

Mesclagem (Merge): Após aprovação e resolução de quaisquer problemas identificados durante a revisão, o novo branch é mesclado de volta ao branch principal. Isso integra as alterações realizadas no desenvolvimento da nova funcionalidade ao código principal.
