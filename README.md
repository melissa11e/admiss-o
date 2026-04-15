# admiss-o
Esse código automatiza uma tarefa repetitiva que estava na minha rotina.
Antes eu precisava baixar de um site uma pasta com documentos de todos os funcionários admitidos em determinado mês. Essas pastas vinham de 50 em 50 e em zips que muitas vezes davam erro na hora de extraí-los.
Para isso, fiz um pequeno algoritmo onde basta apenas você deixar os zips com as 50 pastas dentro de uma pasta, e ele automaticamente extrai tudo, deixando todos em uma pasta normal. Se houverem nomes grandes ou repetidos, o algoritmo consegue ter o controle durante a extração e resolver sozinho.
Outra etapa que antes era manual, consistia no fato de que todas essas pastas precisavam ter seu nome alterado de data - cd_vaga - nome para cpf_matricula.
Para isso, fiz uma relação com 2 tabelas diferentes, uma que relaciona o cd_vaga ao CPF do funcionário e outra que relaciona o CPF com a matrícula.
Assim, os nomes são automaticamente alterados, sem exigir muitos esforços do usuário do código.
- Algo que eu ainda sinto que preciso solucionar é o título de cada etapa do processo, onde selecionamos as planilhas, pastas de origem e pastas de destinos, pois para alguém leigo ainda é difícil de compreender.
