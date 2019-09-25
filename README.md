## Firewall Jubarte


#Segurança da Informação:

Informação é algo que precisa ser protegido, independente de serem empresas ou serviços públicos e do porte desses responsáveis a perda de informações pode significar grandes riscos a seu futuro e até da segurança de usuários que dependem deles. A topologia de rede local das instituições pode sempre estar à mercê de ataques devido às suas vulnerabilidades, sendo assim é de grande importância que existam ações com o objetivo de proteger a informação. 

#Ferramentas de Segurança...

Existem protocolos e ferramentas de segurança de redes que visam proteger pontos específicos das topologias, grande parte delas são livres e gratuitas, mas dependem de conhecimento conciso de redes de computadores, além de serem segmentados, onde cada ferramenta tem funções específicas de detecção e/ou prevenção, além de ferramentas de redes de ação mais genérica que, entre outras, podem realizar funções de segurança. Sendo assim um sistema que garanta maior proteção para a rede local deve conter uma série de ferramentas que contemple as diversas camadas de operação, monitore o tráfego que entra e sai e também possa dá maneira mais automática possível agir contra prováveis ataques, tudo isso mantendo o maior número de registros possíveis (chamado no meio de log) para melhorias futuras. 

#Um projeto de TCC

A proposta de projeto para a matéria de Tópicos Especiais é levantar uma ambiente de Firewall operacional que rode as aplicações de segurança em Dockers, dando a ele modularidade de aplicações, persistência de execução das aplicações, isolamento de serviços e uma boa gestão das ferramentas como um todo.

Além do Docker propriamente dito será necessário uma maneira de realizar a chamada “orquestração” de containers, que pode ser feita por meio de shell scripts ou outras ferramentas próprias para tal como o Kubernetes. Também será necessário trabalhar com base em uma distribuição Linux, que tem o maior suporte não apenas ao Docker mas também a maioria das ferramentas de rede disponíveis. Um estudo sobre as aplicações de seguranças deverá ser feita, de preferência tentar englobar o maior número de possibilidades de vulnerabilidades existentes em topologias de rede.

	A príncipio o projeto funcionará em apenas um desktop normal

#Para o futuro

Após a implementação ser realizada numa única máquina a ideia é ampliar para que o firewall funcione em máquinas diferentes, num cluster. E será utilizado raspberrys para diminuir os custos e gastos de consumo


#Nome do projeto

O simbolo do docker é uma baleia carregando containers como se fosse um navio de carga

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

