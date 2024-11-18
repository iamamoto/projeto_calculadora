# projeto_calculadora
 Projeto 1 do Curso de Analista de Dados - EBAC

Para executar o arquivo .sh:
   - Alocar os arquivos 'calculadora.sh' e 'calculadora.py' em um repositório linux
   - Se necessário alterar o caminho do arquivo 'calculadora.py' informado no script .sh
   - Em um terminal de controle linux, acessar o diretório que está o arquivo 'calculadora.sh', utilizando comando cp e executar o arquivo da 
     forma: ./calculadora.sh
     
Sobre o código:
   - Rotina para executar 4 tipos de cálculo entre 2 números:
        - Soma
        - Subtração
        - Multiplicação
        - Divisão
    
   - No início será solicitado ao usuário que digite dois números (inteiros ou reais)
   - Em seguida entrá em um loop que irá solicitar ao usuário qual operação realizar:
        1. Somma
        2. Subtração
        3. Multiplicação
        4. Divisão
        5. Sair
     Realizando o cálculo de acordo com a opção escolhida, a opção 5, sai do loop e encerra a rotina

   - Caso o usuário escolha qualquer outro número, que não esteja entre 1 e 5, será apresentada mensagem de opção inválida e solicitará        novamente uma opção
