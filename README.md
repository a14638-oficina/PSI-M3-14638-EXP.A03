# PSI - M3 - PROGRAMACAOESTRUTURADA - EXP.A03
<h1>Introdução</h1>
O código implementa um sistema de gestão de stock de materiais, com funcionalidades que permitem ao utilizador adicionar, consultar, atualizar e exibir o stock de materiais. As informações sobre o stock também podem ser gravadas num arquivo de texto.
<h1>Problema</h1>
O código precisa fornecer uma interface para que os utizadores possam gerir o stock de materiais de maneira eficiente. O sistema deve permitir adicionar materiais, consultar a quantidade existente, atualizar o stock (adicionando ou removendo unidades) e exibir o estado atual do stock.
<h1>Requisitos </h1>
O código deve:
Adicionar materiais ao stock, verificando se o material já existe.
Consultar o stock de um material específico.
Atualizar o stock, permitindo adicionar ou remover unidades de um material.
Exibir o stock geral em formato tabular.
Salvar o estado do stock em um arquivo de texto (stock.txt) para armazenamento persistente.
<h1>Estrutura do Código (Python) </h1>
Funções:

adicionar_material(stock):

Solicita o nome e a quantidade inicial de um material.
Verifica se o material já está presente no stock e, em caso negativo, adiciona o material ao dicionário stock.
consultar_stock(stock):

Solicita o nome de um material e exibe a quantidade disponível, caso o material exista no stock. Caso contrário, informa que o material não foi encontrado.
atualizar_stock(stock):

Permite adicionar ou remover unidades de um material existente no stock. Verifica a validade da operação (se a quantidade a ser removida não excede a disponível).
exibir_stock(stock):

Exibe o estado atual de todos os materiais no stock, apresentando o nome do material e a quantidade disponível.
Escreve as informações de stock no arquivo stock.txt, utilizando a função f.write().

Apresenta um menu interativo para o utilizador, com opções para adicionar, consultar, atualizar ou exibir o stock. O programa continua em loop até que o utilizador opte por sair.
Fluxo de Execução:

O usuário escolhe a operação desejada no menu. As funções são chamadas de acordo com a escolha do utilizador, permitindo a manipulação do stock.
O programa termina quando a opção "Sair" é escolhida.
