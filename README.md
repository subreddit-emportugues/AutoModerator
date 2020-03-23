# Auto-moderador

## Descrição
Auto-moderador do Reddit que monitora o cumprimento de quase todas as regras do subreddit [r/EmPortugues](https://www.reddit.com/r/EmPortugues/).

O auto-moderador usa o [u/AutoModerator](https://www.reddit.com/user/AutoModerator/) para checar uma série de detalhes em cada postagem do subreddit seguindo critérios descritos em [YAML](https://pt.wikipedia.org/wiki/YAML) no diretório "/wiki/config/automoderator" com a finalidade de remover todo conteúdo que não respeite as [regras da comunidade](https://www.reddit.com/r/EmPortugues/about/wiki/rules).

As funções exercidas pelo auto-moderador garantem a remoção de postagens com links para domínios diferentes de [reddit.com](https://www.reddit.com/), com links para [old.reddit.com](https://old.reddit.com/), com links HTTP, com links com parâmetros UTM, com títulos sem "r/", textuais e cruzadas e de postagens e de comentários com links para vários sites populares; além de avisar aos moderadores por `modmail`.

As informações conferidas pelo auto-moderador são: `type`, `priority`, `moderators_exempt`, `comment`, `comment_stickied`, `modmail`, `modmail_subject`, `author`, `title`, `body`, `domain`, `action`, `action_reason`, `set_flair`, `overwrite_flair`.

## Sumário
* [Instalação](#Instalação)
* [Instruções](#Instruções)
* [Colaboração](#Colaboração)
* [Demonstração](#Demonstração)
* [Referências](#Referências)

## Instalação
1. Clone o repositório;
2. copie todo o conteúdo de "config.py" e cole o texto em "/wiki/config/automoderator";
3. acesse "/about/moderators" e convide [u/AutoModerator](https://www.reddit.com/user/AutoModerator);
4. e aguarde a aceitação.

## Instruções
Para alterar os tipos de conteúdo, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
type:
```

Para alterar as prioridades das regras, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
priority:
```

Para alterar a exceção à moderação, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
moderators_exempt:
```

Para alterar as respostas às postagens, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
comment:
```

Para alterar os destaques dos comentários, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
comment_stickied:
```

Para alterar as mensagens para os moderadores, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
modmail:
```

Para alterar os assuntos da mensagens, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
modmail_subject:
```

Para alterar detalhes sobre os autores, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
author:
```

Para alterar detalhes sobre os títulos, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
title:
```

Para alterar detalhes sobre os textos, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
body:
```

Para alterar detalhes sobre os domínios, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
domain:
```

Para alterar as atitudes tomadas, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
action:
```

Para alterar as razões das remoções, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
action_reason:
```

Para alterar as categorias das postagens, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
set_flair:
```

Para alterar flairs já escolhidas, em [config.yml](https://github.com/subreddit-emportugues/auto-moderador/blob/master/config.yml), edite:
```
overwrite_flair:
```

## Colaboração

Você pode colaborar com o desenvolvimento deste projeto! 

[Confira os kanbans deste projeto](https://github.com/orgs/subreddit-emportugues/projects/6), [entre em contato com a equipe de moderação](https://reddit.com/message/compose?to=/r/EmPortugues) e [participe da equipe de desenvolvimento](https://github.com/orgs/subreddit-emportugues/teams/desenvolvedores) para saber a respeito do progresso deste repositório caso queira colaborar antes de [reportar um novo problema](https://github.com/subreddit-emportugues/auto-moderador/issues) ou [solicitar o recebimento de uma modificação](https://github.com/subreddit-emportugues/auto-moderador/pulls).

## Demonstração

[Conheça o auto-moderador para entender como o código deste repositório funciona.](https://www.reddit.com/user/AutoModerator)

## Referências

* Auto-moderador: https://www.reddit.com/user/AutoModerator
* Comunidade: https://www.reddit.com/r/EmPortugues
* Organização: https://github.com/subreddit-emportugues
* Repositório: https://github.com/subreddit-emportugues/auto-moderador
* Projeto: https://github.com/orgs/subreddit-emportugues/projects/6
* Equipe: https://github.com/orgs/subreddit-emportugues/teams/desenvolvedores
* Licença: https://github.com/subreddit-emportugues/auto-moderador/blob/master/LICENSE
