Simulador de Saque em Caixa Eletrônico
Informações Básicas

Este programa simula o funcionamento de um caixa eletrônico para realizar saques em dinheiro. Ele garante que o valor do saque seja um múltiplo positivo de 5 e calcula automaticamente quantas notas de cada denominação (50, 20, 10 e 5 reais) são necessárias para o valor solicitado.

Descrição
O programa é desenvolvido em C++, utilizando funções para validar o valor do saque, calcular as notas necessárias e exibir o resultado ao usuário. Funciona em um loop que permite múltiplos saques até que o usuário decida encerrar o programa.

Função validaValor(int saque): Verifica se o valor do saque é positivo e múltiplo de 5.

Função contaNotas(int saque): Calcula o número de notas de 50, 20, 10 e 5 reais necessárias para o valor de saque fornecido.

Função exibeNotas(const array<int, 4>& notas): Exibe na tela a quantidade de cada nota utilizada no saque.

Função executaCaixaEletronico(): Função principal que interage com o usuário, solicitando o valor do saque, verificando sua validade, calculando as notas necessárias e exibindo o resultado.

Função main(): Inicia o programa, permitindo que o usuário faça múltiplos saques. Após cada transação, pergunta ao usuário se deseja realizar outro saque.

Licença
Este programa está disponível sob a licença MIT, que permite o uso, cópia, modificação, fusão, publicação, distribuição, sublicenciamento e/ou venda de cópias do software, mediante a inclusão do aviso de direitos autorais original e da permissão dada na licença.

Exemplo de Uso
Digite o valor a ser sacado: O usuário insere um valor desejado para sacar.

Validação do valor: O programa verifica se o valor é um múltiplo positivo de 5. Caso contrário, informa que o valor é inválido e pede outro valor.

Cálculo das notas: Se o valor for válido, o programa calcula automaticamente o número de notas de cada denominação (50, 20, 10, 5 reais) necessárias para compor o valor do saque.

Exibição do resultado: O programa mostra ao usuário quantas notas de cada valor serão dispensadas.

Opção de novo saque: Após exibir o resultado, pergunta ao usuário se deseja realizar outro saque. Se sim, o processo se repete; se não, o programa é encerrado.

Considerações Finais
Este simulador de caixa eletrônico foi projetado para ser simples e eficiente, garantindo uma experiência amigável ao usuário ao realizar operações de saque de maneira segura e rápida.

Espero que essa documentação te ajude a entender melhor como o programa funciona e como ele pode ser utilizado!



