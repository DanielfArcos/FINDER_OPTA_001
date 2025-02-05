# C-_FINDER_OPTA_001

Essa programação foi desenvolvida em C++ para o Finder OPTA com o principal objetivo de fazer interação entre os núcleos do produto (M7 e M7). Onde um pulso no botão do usuário do produto será interpretado no núcleo M7, este pulso é processado e o núcleo M4 executa uma função com base neste pulso. Neste exemplo de demonstração, o LED_D0 é ativado com base na atuação do botão do usuário OPTA.

> [!NOTE]
> Para programação chamada OPTA-PROG-PROCESSOR-INTERACTION-M7, siga estas configurações:
> 
> Tools > Flash split > 1MB M7 + 1MB M4
> 
> Tools > Target core > Main Core
> 
> Depois de terminar de configurar isso, você pode enviar a programação para o produto.


> [!NOTE]
> Para programação chamada OPTA-PROG-PROCESSOR-INTERACTION-M4, siga estas configurações:
> 
> Tools > Flash split > 1MB M7 + 1MB M4
> 
> Tools > Target core > M4 Co-processor
> 
> Depois de terminar de configurar isso, você pode enviar a programação para o produto.
