

#  Git e GitHub

![](./imagens/git-githu-cover.png)



Trabalhar com controle de versão é uma habilidade essencial para qualquer pessoa que queira trabalhar desenvolvimento relacionado a software.

Conteúdo extraido e adaptado do WoMakersCode.

Neste curso básico, você aprenderá sobre:

1. [Criando uma conta no GitHub](git-e-github/setup.md)
2. [Setup de instalação](git-e-github/setup-de-instalacao.md)
3. [Vocabulário](git-e-github/conceitos-e-vocabulario-do-git.md)
4. [Comandos mais utilizados](git-e-github/comandos-mais-utilizados.md)
5. [Restringindo arquivos com .gitignore](git-e-github/o-que-e-o-.gitignore.md)
6. [Dicas de boas práticas](git-e-github/dicas-de-boas-praticas.md)
7. [Práticas](git-e-github/hands-on/)




#   Por que usar Git e GitHub?
Git e Github são utilizados no dia a dia das pessoas que criam software por um motivo bem simples: ter uma forma fácil de gerenciar o código fonte da aplicação, do sistema, do produto.

Em um time pequeno, algumas pessoas ainda tentam tomar conta desses arquivos de maneiras um tanto questionáveis: compartilhar diretórios na rede, utilizar ferramentas como Dropbox, ou manter tudo em um servidor de FTP. Práticas totalmente desaconselhadas.

#   O que é Git? um Sistema de Controle de Versão
Apenas poder acessar o código dos outros colaboradores não é suficiente. Precisamos manter o histórico dos nossos arquivos. Mais: das nossas modificações, pois muitas vezes mudamos arquivos em grupo, num movimento único (um commit). Dessa forma, podemos voltar atrás e recuperar o estado do sistema como ele era ontem, ou no ano passado, e comparar as mudanças, para encontrar bug, para estudar otimizações.

Todos nossos arquivos, assim como seus históricos, ficam em um repositório e existiam vários sistemas que gerenciavam repositórios assim, como CVS e SVN. O Git é uma alternativa que tem um funcionamento mais interessante ainda: ele é distribuído e todo mundo tem uma cópia inteira do repositório, não apenas o "servidor principal". Isso trás grandes vantagens que você não precisa aprender nesse exato momento.

O Git é um sistema de controle de versão distribuído e amplamente adotado. O Git nasceu e foi tomando espaço dos outros sistemas de controle. Seu criador principal é o mesmo que o do Linux: Linus Torvalds, e ganhou o coração das pessoas que trabalham com open source.


#   O que é GitHub?
O Github tem sim muita relação com o Git. GitHub é uma plataforma para gerenciar seu código e criar um ambiente de colaboração entre devs, utilizando o Git como sistema de controle. Ele vai facilitar o uso do Git, escondendo alguns detalhes mais complicados de setup. É lá que você provavelmente vai ter seu repositório e usar no dia a dia.