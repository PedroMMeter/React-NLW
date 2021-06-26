# React-NLW

Letmeask é uma aplicação que permite um criador de conteúdo interagir com a sua comunidade
respondendo suas duvidas, onde o anfitrião cria a sala e os demais podem entrar nela através do código e enviar suas perguntas.

A aplicação é focada para algo em tempo real, já que a mesma não recebe um campo para respostas em texto, então ela funciona melhor
em streams, para tornar mais facil de ler e responder aquilo que os "viewers" normalmente enviariam no chat da stream.

Outra funcionalidade interessante, é que ela pode ser utilizada para realizar vídeos futuros, por exemplo:
O criador de conteúdo abre uma sala, os "viewers" mandam as perguntas, e as mesmas serão respondidas num vídeo que irá ao ar no Youtube.


Eu realizei algumas alterações na aplicação. Onde antes, ao criar a sala, você era redirecionado à página de usuário padrão e não de administrador. 
Agora ao entrar numa sala pelo código você é obrigado a fazer o login, e caso entre diretamente pelo endereço da página, haverá um link abaixo da aba de perguntas
que vai redireciona-lo à home da app, para que você entre com o código da sala, realizando o login (caso tenha realizado o login alguma outra vez, outra sala,
você pode entrar pelo link, já que suas credenciais de usuário já estarão salvas e preenchidas pelo sistema).
