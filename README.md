# firewall-jubarte



Informação é algo que precisa ser protegido, independente de serem empresas ou serviços públicos e do porte desses responsáveis a perda de informações pode significar grandes riscos a seu futuro e até da segurança de usuários que dependem deles. A topologia de rede local das instituições pode sempre estar à mercê de ataques devido às suas vulnerabilidades, sendo assim é de grande importância que existam ações com o objetivo de proteger a informação. 
Existem protocolos e ferramentas de segurança de redes que visam proteger pontos específicos das topologias, grande parte delas são livres e gratuitas, mas dependem de conhecimento conciso de redes de computadores, além de serem segmentados, onde cada ferramenta tem funções específicas de detecção e/ou prevenção, além de ferramentas de redes de ação mais genérica que, entre outras, podem realizar funções de segurança. Sendo assim um sistema que garanta maior proteção para a rede local deve conter uma série de ferramentas que contemple as diversas camadas de operação, monitore o tráfego que entra e sai e também possa dá maneira mais automática possível agir contra prováveis ataques, tudo isso mantendo o maior número de registros possíveis (chamado no meio de log) para melhorias futuras. 
O nome aplicado no meio é Tecnologia da Informação para esse sistema de proteção é Firewall. Cada topologia de rede pode ter necessidades diferentes para o seu Firewall, dessa maneira uma ferramenta pronta e unificada dificilmente seria possível. Diferente de algo modular, uma sistema empilhável que pode ser ampliado sempre que necessário. Existem hoje aplicações como o docker que podem rodar as ferramentas de segurança de maneira mais independente dos resto da topologia e até mesmo da máquina que está destinada a esse fim, o que facilita a criação de um ambiente que possa se integrar com processos novos quando a necessidade de alteração e ampliação, além das vantagens iniciais de rodar serviços de maneira quase que independente. 
A proposta de projeto para a matéria de Tópicos Especiais é levantar uma ambiente de Firewall operacional que rode as aplicações de segurança em Dockers, dando a ele modularidade de aplicações, persistência de execução das aplicações, isolamento de serviços e uma boa gestão das ferramentas como um todo.
Para realizar esse projeto será necessário que o sistema tenha uma boa responsividade quando necessário realizar manutenção, mudanças de configuração e nas suas operações de monitoramento, também que opere de preferência em máquinas dedicadas a ele para ter os recursos físicos bem aplicados, tenha maior parte das suas funções automatizadas, tenha suporte a boa parte dos tipos de aplicações de segurança em sua base para trabalhar com eles quando necessário.
Além do Docker propriamente dito será necessário uma maneira de realizar a chamada “orquestração” de containers, que pode ser feita por meio de shell scripts ou outras ferramentas próprias para tal como o Kubernetes. Também será necessário trabalhar com base em uma distribuição Linux, que tem o maior suporte não apenas ao Docker mas também a maioria das ferramentas de rede disponíveis. Um estudo sobre as aplicações de seguranças deverá ser feita, de preferência tentar englobar o maior número de possibilidades de vulnerabilidades existentes em topologias de rede.
Caso haja a necessidade de scripts mais complexos a melhor opção a ser usada seria o Python como linguagem de programação, também devido a seu fácil suporte a Linux, integração ao Bash e vasto número de bibliotecas, inclusive algumas nativas para programação em redes.
Para validar o uso do projeto ao final dele seria interessante uma segunda máquina com ferramentas de PenTest para validar a efetividade do ambiente de segurança.


Nome do projeto

O simbolo do docker é uma baleia carregando containers
A baleia jubarte (ou HUMPBACK WHALE) é conhecida por ter um comportamento altruísta ao defender outros animais de seu ecossistema de preadores

Dessa maneira o nome escolhido foi o de FIREWALL JUBARTE
	Ou caso fique melhor em inglês HUMPBACK WHALE FIREWALL
(Vamos ver qual nome é mais maneiro ainda)....


Docker e baleias:
http://www.sinestec.com.br/blog/por-que-docker/

Jubarte tem comportamento protetor
https://www.nationalgeographicbrasil.com/animais/2018/01/baleia-supostamente-protege-mergulhadora-de-tubarao
https://www.veggietal.com.br/baleia-protege-animais-predacao/
http://tafi.com.br/2018/01/10/baleia-jubarte-protege-mergulhadora-de-um-ataque-de-tubarao/
https://fatosdesconhecidos.ig.com.br/veja-uma-baleia-jubarte-salvando-um-mergulhador-de-um-tubarao/

