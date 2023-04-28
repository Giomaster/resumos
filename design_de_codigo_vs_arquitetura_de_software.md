# Design de Código VS Arquitetura de Software

No mundo da tecnologia os **dados são reis**! Até porque o desenvolvimento de software no geral é a manipulação de dados conforme as necessidades dos usuários. Porém é justamente por isso que precisamos ter muito **cuidado ao iniciar um novo projeto**, sem os devidos planejamentos o projeto terá caracteristicas muito negativas que são:

* Ilegibilidade
* Inflexibilidade
* Falta de manutenibilidade
* Entre outros

Um projeto com essas caracteristicas pode até ser concluida, entretanto se for necessário algum ajuste ou atualização, os desenvolvedores vão ter muito esforço ou simplesmente não conseguirão sustentar esse projeto.

Por isso ao longo dos anos o ser humano foi desenvolvendo métodos de planejamento e filosofias para sempre manter os seus projetos o mais simples e organizado possível.

## Arquitetura de Software

Em tempos antigos ao construir um sistema, o código era construído como um monolito para todo tipo de projeto. **A problemática em si não é questão de usar monolitos, mas usá-la em TODO tipo de projeto.** Porque monolitos tem a desvantagem de todos os seus componentes serem interdependentes, o que com descuido pode acarretar em uma grande falta de manutenibilidade.

A *arquitetura de software* veio para isso! Esse conceito existe para mapear os componentes que existirão e como eles vão interagir entre eles. Atualmente tem várias estratégias de *arquitetura de software* que podem ser utilizadas nos projetos, como por exemplo:

* MVC *(Model, View and Controller)*
* Layers *(Camadas)*
* Microservices *(Microsserviços)*
* Entre outros

A intenção aqui não é detalhar de cada estratégia de *arquitetura de software* e então eleger a melhor estratégia, até porque **não existe a melhor estratégia mas sim as melhores estratégias para o seu projeto**. E para conseguir ter o senso critico de qual estratégia utilizar, apenas basta entender em essência que o seu projeto antes de tudo precisa ser mapeado e como será as suas interações entre eles.

![Arquitetura Limpa](images/ddc_vs_ads/clean_architecture.png)

A imagem acima mostra um exemplo de uma *arquitetura limpa*. E como podemos observar, ela é divida entre 4 camadas:

* **Framework & Drivers**: Responsável pelas interações externas
* **Interface Adapters**: Responsável por encaminhar as informações adquiridas pelos *Framework & Drivers* para a aplicação de fato.
* **Use Cases**: <TODO_DESCRIPTION>
* **Entities**: <TODO_DESCRIPTION>
