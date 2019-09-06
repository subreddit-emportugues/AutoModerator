# AutoModerator

## Descrição
Auto-moderador do Reddit que monitora o cumprimento de quase todas as regras do subreddit [r/EmPortugues](https://www.reddit.com/r/EmPortugues/).

O auto-moderador usa o [u/AutoModerator](https://www.reddit.com/user/AutoModerator/) para checar uma série de detalhes em cada postagem do subreddit seguindo critérios descritos em [YAML](https://pt.wikipedia.org/wiki/YAML) no diretório "/wiki/config/automoderator" com a finalidade de remover todo conteúdo que não respeite as [regras da comunidade](https://www.reddit.com/r/EmPortugues/about/wiki/rules).

As funções exercidas pelo auto-moderador garantem a remoção de postagens com links para domínios diferentes de [reddit.com](https://www.reddit.com/), com links para [old.reddit.com](https://old.reddit.com/), textuais e cruzadas e de postagens e de comentários com links para vários sites populares, com títulos sem "r/" e de contas novas e com pouco karma; além de avisar aos moderadores por `modmail`.

As informações analisadas pelo auto-moderador são: `~domain`, `domain`, `type`, `domain+body`, `~title (includes)`, `author: account_age` e `author: combined_karma`.

## Sumário
* [Instalação](#Instalação)
* [Instruções](#Instruções)
* [Dependências](#Dependências)
* [Colaboração](#Colaboração)
* [Demonstração](#Demonstração)
* [Referências](#Referências)

## Instalação
1. Baixe o repositório;
2. copie todo o conteúdo de "config.py";
3. cole o texto em "/wiki/config/automoderator";
4. acesse "/about/moderators" e convide [u/AutoModerator](https://www.reddit.com/user/AutoModerator);
5. e aguarde a aceitação.

## Instruções
Para alterar os tipos de conteúdo, em [config.yml](https://github.com/subreddit-emportugues/AutoModerator/blob/master/config.yml), edite:
```
type:
```

Para alterar as prioridades das regras, em [config.yml](https://github.com/subreddit-emportugues/AutoModerator/blob/master/config.yml), edite:
```
priority:
```

Para alterar as respostas às postagens, em [config.yml](https://github.com/subreddit-emportugues/AutoModerator/blob/master/config.yml), edite:
```
comment:
```

Para alterar as mensagens para os moderadores, em [config.yml](https://github.com/subreddit-emportugues/AutoModerator/blob/master/config.yml), edite:
```
modmail:
```

Para alterar os atitudes tomadas, em [config.yml](https://github.com/subreddit-emportugues/AutoModerator/blob/master/config.yml), edite:
```
action:
```

## Dependências
> config
```
/wiki/config/automoderator
```

> u/AutoModerator
```
/about/moderators
```

## Colaboração

Você pode colaborar com o desenvolvimento deste repositório!

[Leia as diretrizes para colaboração](/CONTRIBUTING.md) antes de [reportar um novo problema](https://github.com/subreddit-emportugues/AutoModerator/issues) ou [solicitar o recebimento de uma modificação](https://github.com/subreddit-emportugues/AutoModerator/pulls).

E [confira os kanbans deste projeto](https://github.com/orgs/subreddit-emportugues/projects/6) e [participe da equipe do auto-moderador]() para saber a respeito do progresso deste repositório caso queira colaborar.

## Demonstração

[Conheça o auto-moderador para entender como funciona.](https://www.reddit.com/user/AutoModerator)

![](/automoderador.gif)

## Referências

* Auto-moderador: https://www.reddit.com/user/AutoModerator
* Comunidade: https://www.reddit.com/r/EmPortugues
* Organização: https://github.com/subreddit-emportugues
* Repositório: https://github.com/subreddit-emportugues/AutoModerator
* Projeto: https://github.com/orgs/subreddit-emportugues/projects/6
* Equipe:
* Licença:
