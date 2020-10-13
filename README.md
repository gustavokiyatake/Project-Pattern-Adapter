# Adapter Pattern
Objetivo
O Padrão Adapter converte uma interface de uma classe para outra interface que o cliente espera encontrar. O Adaptador permite que classes com interfaces incompatíveis trabalhem juntas.

# Motivação
O padrão Adapter é muito utilizado quando precisamos encaixar uma nova biblioteca de classes, adquirida de um fornecedor, em um sistema de software já existente, porém essas bibliotecas de classe do novo fornecedor são diferentes das bibliotecas de classes do fornecedor antigo. Como não temos o código do novo fornecedor e também não podemos alterá-la, o que pode ser feito é criar uma classe que faça essa adaptação, ou seja, ela é responsável por adaptar a interface do novo fornecedor ao formato que o sistema espera.

# Aplicabilidade
O Adapter é muito utilizado para compatibilizar o seu sistema a outros frameworks ou APIs.

# Estrutura
![structure](http://videos.web-03.net/artigos/Higor_Medeiros/PadraoAdapter_Java/PadraoAdapter_Java1.jpg)

# Participantes
#### Client
Que é quem acessa a interface do Adaptador e a partir desta interface ele fará uma solicitação ao adaptador. 

#### Adaptador
Implementa a interface alvo (Target) e comunica-se com o Adaptado (Adaptee). 

#### Adaptee
É a nova biblioteca do fornecedor que está sendo inserida no sistema. No exemplo ficará mais clara a função de cada um dos elementos explicitados no diagrama de classes acima.

# Exemplo de Implementação
