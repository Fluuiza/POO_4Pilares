ATIVIDADE AVALIATIVA:
Aprendemos que são 4 pilares da orientação a objetos em utilizadas em linguagens de programação orientadas a objetos: Herança, Encapsulamento, Polimorfismo e Abstração. Crie exemplos práticos com Java com cada uma delas, utiliza analogia para cada explicá-las.


POO_4Pilares – Sistema de Formas de Pagamento em Java

 ├── poo.com.br.abstracao
 
 ├── poo.com.br.heranca
 
 ├── poo.com.br.encapsulamento
 
 └── poo.com.br.polimorfismo
 
___________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Resumo do Projeto

Este projeto foi desenvolvido em Java com o objetivo de demonstrar, de forma prática, os quatro pilares da Programação Orientada a Objetos (POO): Abstração, Herança, Encapsulamento e Polimorfismo.
Para representar esses conceitos, foi criado um sistema simples de formas de pagamento, permitindo simular pagamentos por Pix, Cartão de Crédito, Cartão de Débito e Dinheiro.

Abstração: foi utilizada para representar a ideia geral de um pagamento. Foi criada uma estrutura base que define o comportamento comum dos métodos de pagamento, permitindo que cada tipo implemente sua própria forma de processamento.7

Analogia: Assim como uma pessoa sabe que precisa pagar uma compra, ela não precisa conhecer todos os detalhes internos de como cada forma de pagamento funciona.

___________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Herança: foi aplicada por meio da classe principal FormaPagamento, da qual as classes Pix, Cartão e Dinheiro herdam características e comportamentos. Dessa forma, evita-se a repetição de código e facilita-se a organização do sistema.

Analogia: Uma família compartilha características em comum, mas cada integrante possui suas próprias particularidades.

____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Encapsulamento: foi demonstrado utilizando atributos privados e métodos de acesso (get e set), protegendo os dados do pagamento e permitindo que eles sejam manipulados de forma segura.

Analogia: Um cofre protege seu conteúdo. Apenas quem possui a chave pode acessar ou modificar o que está armazenado.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Polimorfismo: foi utilizado para permitir que diferentes formas de pagamento executem o mesmo método, porém com comportamentos diferentes. Assim, uma mesma referência pode representar objetos distintos, como Pix, Cartão ou Dinheiro.

Analogia: Um controle remoto possui o botão "Ligar", mas cada aparelho reage de maneira diferente ao receber esse comando.

_____________________________________________________________________________________________________________________________________________________________________________________________________________________________________________

Conclusão

Este projeto permitiu aplicar na prática os conceitos fundamentais da Programação Orientada a Objetos. A utilização de um sistema de formas de pagamento tornou mais fácil compreender como os quatro pilares trabalham em conjunto para criar um código organizado, reutilizável, seguro e de fácil manutenção.

