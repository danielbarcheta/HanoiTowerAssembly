<h1 align="center"> Hanoi Tower - Assembly</h1><br>


A implementação em Assembly do algoritmo Torre de Hanoi consiste em resolver um quebra-cabeça desenvolvido por Édouard Lucas em 1883. O jogo envolve três pinos/postes, onde os discos são alocados. O objetivo é mover os discos de um poste para outro, colocando-os em ordem crescente de diâmetro. O algoritmo utiliza recursão para solucionar o problema de forma eficiente.

<h2>🔍 Visão Geral</h2>
A implementação em Assembly do algoritmo Torre de Hanoi consiste em resolver um quebra-cabeça desenvolvido por Édouard Lucas em 1883. O jogo envolve três pinos/postes, onde os discos são alocados. O objetivo é mover os discos de um poste para outro, colocando-os em ordem crescente de diâmetro. O algoritmo utiliza recursão para solucionar o problema de forma eficiente.

📜 Código Explicado
O código em Assembly possui várias seções explicadas abaixo:

<b>a) Seção .data</b>
Nesta seção, são alocadas as strings utilizadas para exibir mensagens durante a execução do código. As mensagens incluem instruções para digitar o número de discos e informações sobre os movimentos dos discos nos postes.

<b>b) Procedimento torredeHanoi</b>
Este é o procedimento principal do algoritmo. Ele inicializa os registradores e executa as operações do algoritmo. Os registradores $s0...$s3 são usados para armazenar os parâmetros necessários para a recursão. O algoritmo utiliza desvios condicionais e chamadas de procedimentos para solucionar o quebra-cabeça.

<b>c) Procedimentos de recursão</b>
Existem dois procedimentos de recursão: recursao1 e recursao2. Eles correspondem às chamadas recursivas feitas pelo procedimento principal torredeHanoi. Os parâmetros são ajustados e o fluxo de instruções é desviado novamente para torredeHanoi. Esses procedimentos são responsáveis por mover os discos entre os postes de acordo com as regras do jogo.

<b>d) Procedimento saidaerestauracao</b>
Este procedimento auxiliar restaura os registradores salvos na pilha durante a recursão. Os registradores são carregados de volta e as posições alocadas na pilha são desempilhadas. Em seguida, o fluxo de instruções retorna para o endereço de retorno salvo em $ra.

<b>e) Procedimento saida</b>
Este procedimento é chamado recursivamente pelo método torredeHanoi para exibir as movimentações dos discos nos postes. Ele utiliza chamadas de sistema para imprimir as mensagens na saída do console. As informações dos registradores $s0...$s2 sobre a posição e o número de discos são passadas como parâmetros para exibição.

<b>f) Método main</b>
O método main define o parâmetro principal do quebra-cabeça, que é a quantidade de discos a serem dispostos no poste A. O usuário é solicitado a inserir um número inteiro, que é lido e passado como parâmetro para a execução do algoritmo torredeHanoi. Os outros parâmetros são definidos e o procedimento torreHanoi é chamado.

<h1 align="center">💻 Executando o Código</h1><br>

Para executar o código Assembly MIPS da Torre de Hanoi, você precisará de um ambiente de desenvolvimento que seja capaz de montar e executar programas MIPS. Você pode utilizar um emulador MIPS, como o MARS (MIPS Assembler and Runtime Simulator), ou qualquer outro ambiente compatível.

Clone ou faça o download deste repositório.
Abra o arquivo do código-fonte Assembly MIPS em seu ambiente de desenvolvimento.
Monte e execute o programa.
Siga as instruções fornecidas pelo programa para fornecer o número de discos e observar a solução para o problema da Torre de Hanoi.
Divirta-se explorando a implementação da Torre de Hanoi em Assembly MIPS e desvendando os segredos desse desafiador quebra-cabeça matemático.
