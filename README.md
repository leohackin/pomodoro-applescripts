Pomodoro AppleScripts
===========================

Scripts de automatização de tarefas para o sofware Pomodoro, do Ugo Landini. O software e mais informações podem ser encontrados em [http://pomodoro.ugolandini.com](http://pomodoro.ugolandini.com). Os scripts foram feitos inicialmente para trabalhar integrar-se aos softwares:

* [Twitter](http://itunes.apple.com/us/app/twitter/id409789998?mt=12) (rede social)
* [Adium](http://adium.im/) (messenger)
* [Things](http://culturedcode.com/things/) (software de GTD - Get Things Done)

Os scripts são escritos em AppleScript e foram testados no Pomodoro versões 0.31 (freeware) e 1.2.2 (disponivel na Mac App Store ou buildada via XCode).

Instalação
-------
Para inserir um AppleScript em seu programa Pomodoro, abra-o e clique em **Preferences**. Em seguida, clique em **Scripts**. Você verá todas as ações do Pomodoro e um campo onde poderá escrever ou inserir seus scripts. Copie o código dos arquivos, de acordo com a ação, para estes campos e faça um teste criando e terminando um Pomodoro. :)

start.pomo
-------
* fecha Twitter
* troca status do Adium para Away e cadastra respostas automáticas
* cria nova task no Things na lista Today

restart.pomo
-------
* abre Twitter
* troca status do Adium para Available e desabilita respostas automáticas

end.pomo
-------
* abre Twitter
* troca status do Adium para Available e desabilita respostas automáticas
* altera task no Things para completed

Customização
-------
Para extender os scripts basta um conhecimento básico em AppleScript. O Pomodoro tem algumas variáveis de notificação que podem ser conhecidas em [http://pomodoro.ugolandini.com/pages/pages/docs-variables.html](http://pomodoro.ugolandini.com/pages/pages/docs-variables.html).

Para testar os scripts, utilize o **Editor AppleScript**, que vem instalado nativamente em seu MacOSX.

Licença
--------
<Pomodoro AppleScripts>
Copyright (C) <2011>  Léo Hackin <leohackin@gmail.com>

This program is free software: you can redistribute it and/or modify
it under the terms of the GNU General Public License as published by
the Free Software Foundation, either version 3 of the License, or
(at your option) any later version.

This program is distributed in the hope that it will be useful,
but WITHOUT ANY WARRANTY; without even the implied warranty of
MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the
GNU General Public License for more details.

You should have received a copy of the GNU General Public License
along with this program.  If not, see <http://www.gnu.org/licenses/>

**Contribua e bons pomodoros! :)**

