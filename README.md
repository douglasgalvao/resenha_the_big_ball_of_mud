# resenha_the_big_ball_of_mud
BIG BALL OF MUD


Resenha: BIG BALL OF MUD – Desafios e Reflexões sobre a Arquitetura de Software Mal Organizada

A grande bola de neve é um termo que foi popularizado por Brian Foote e Joseph Yoder para descrever softwares
que são dificeis de manter,de entender, é caótico é complexo, e que
Embora funcione a manuntenção se torna um desafio constante, por que não segue as boas práticas de engenharis de softwares
Mas como poderiamos melhorar? como poderiamos não fazer tão ruim assim?, no artigo Big Ball of Mud é apresentado seis padrões
que vou comentar logo abaixo:

- BIG BALL OF MUD -> Acoplamento e complexidade, tudo para fazer funcionar sem se preocupar com o quao caótico a sua arquitetura/projeto/código ficará.

- THROWAWAY CODE ->  Código escrito rapidamente sem consideração para reutilização ou manutenção a longo prazo. implementado para 
 atender a uma necessidade imediata, com a intenção de ser descartado, mas muitas vezes permanece no sistema, 
 contribuindo para a desordem.

- PIECEMEAL GROWTH -> O sistema evolui de maneira incremental, sem um planejamento centralizado, resultando em uma expansão gradual 
e desorganizada. Mudanças são feitas de forma ad hoc, à medida que novos requisitos surgem, levando ao Grande bola de Lama, a verdadeira bola de Lama de código.

- KEEP IT WORKING -> Como a frase já diz, continue funcionando, que eu acho que combina muito com o ágil, pelo ágil ter surgido na area de negócios
e ser também feito para atender as necessidades do negócio, a ideia é manter o código funcionando mesmo incrementando sempre novas funcionalidades.
O Keep it Working não liga para soluções de curto prazo, com tanto que continue mantendo o sistema funcionando.

- SWEEPING IT UNDER THE RUG -> O famoso esconder a poeira de baixo do tapete, parece ser algo não preocupante por exemplo você saber 
que não está implementando uma boa prática, mas consegue contornar o "seu problema" e entregar sua solução mesmo sabendo que posteriormente
o seu código estará comprometido, mas que temporáriamente fica na esperança de que as coisas vão continuar dando certo, que está tudo bem e vamos para outra

- RECONSTRUCTION (Quando a Única Solução é Começar do Zero)-> Isto é, não da mais, fim da linha, invíavel continuar, é quando acontece o proesso de reestruturação ou recontreução
do sistema para melhorar a arquitetura e analisar como as coisas foram pensadas, na verdade como as coisas deveriam ter sido pensadas, é o preço que está sendo pago.
E nesse processo é onde acontece a refatoração e até mesmo reescrita do código, pois uma mudança de arquitetura pode falar se você precisa
de mais ou até de menos código.
O legal é que isso é real, acontece nas empresas desde o começo da tecnologia nas empresas e geralmente é decidido um RECONSTRUCTION
quando chega a um ponto em que a única solução viável é uma reforma significativa, a mudança drástica!.



O Surgimento da Grande bola de Lama
A Grande bola de Lama não surge de forma planejada, mas como resultado de uma combinação de fatores. Entre os principais motivos está a pressão por prazos curtos (igual eu falei acima, o ágil na minha opinião tem prós e contras),
que força os desenvolvedores a tomar decisões rápidas, muitas vezes improvisadas, para garantir que o sistema continue funcionando e que novas funcionalidades
sejam implementadas rapidamente. A necessidade de uma solução rápida frequentemente leva ao uso de CÓDIGO DESCARTÁVEL (THROWAWAY CODE), 
sem considerar sua reutilização ou manutenção futura. Com o tempo, essas decisões faz o sistema mais complexo e difícil de manter.


As Forças que Alimentam a Grande bola de Lama
Além dos padrões já mencionados, o surgimento de uma Grande bola de Lama é impulsionado por diversas forças globais que afetam o desenvolvimento de software. 
A primeira dessas forças é o tempo. Frequentemente, os desenvolvedores estão sob pressão constante para entregar novas funcionalidades rapidamente 
(Não que seja errado, até porque a tecnologia tem que atender os negocios), mas que faz com que 
as decisões arquitetônicasde longo prazo sejam deixadas de lado em favor de soluções imediatas. Mesmo quando há uma intenção de organizar 
o sistema de forma adequada, as demandas por resultados rápidos podem forçar a adoção de soluções temporárias que, com o tempo, se tornam permanentes, e quando vê já foi.



O Círculo Vicioso da Grande bola de Lama
Um detalhe importante da Big Gambiarra (Grande bola de Lama) é o círculo vicioso que se forma ao redor desses sistemas. Conforme o código se deteriora, torna-se mais difícil para os programadores 
navegarem e fazerem mudanças com confiança. Isso leva à adoção de soluções temporárias, que, por sua vez, agravam ainda mais o problema, já que a complexidade do sistema aumenta e os negocios continuam
querendo mais e mais implementações, e o ciclo se repete. Com o tempo, o sistema se torna tão complexo e caótico que a manutenção se torna um desafio constante, e a única solução viável é uma RECONSTRUCTION (reconstrução) 
do sistema, que é um processo caro e demorado, mas que muitas vezes é a única maneira de resolver o problema.
    - A falta de documentação é outro problema comum em sistemas Big Gabiarra (Grande bola de Lama). 


Reflexões Finais
No final das contas, a Grande bola de Lama é um padrão comum, mas indesejado, no desenvolvimento de software. Embora suas falhas arquitetônicas sejam amplamente reconhecidas, 
sua persistência no mercado reflete as pressões e limitações que muitas equipes de desenvolvimento enfrentam. Manter um equilíbrio entre atender às demandas de curto prazo e garantir 
a integridade de longo prazo da arquitetura é um desafio constante para desenvolvedores e gestores de software (e acredito que saber equilibrar esses dois lados de entrega de soluções pro negócio e também 
se preocupar com a qualidade sem afetar areas externas com prazos, é altamente recomendado, porque um tempo n gasto agora, pode ser um tempo n^3 reduzido lá na frente).