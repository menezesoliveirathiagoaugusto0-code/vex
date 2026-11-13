# VEX NEXUS

App estático (HTML) com versão de celular e de TV.

## Publicar
1. Crie um repositório no GitHub e envie estes arquivos na raiz.
2. Na Vercel: Add New > Project > importe o repositório > Deploy (sem configurar nada).
3. Celular: abra o endereço da Vercel. TV: abra o mesmo endereço com `#tv` no final.

## Pareamento
Usa o serviço público ntfy.sh como ponte (sem conta). O código de 6 números vira um canal público, então serve para protótipo. Para produção, troque por Firebase ou um backend próprio (veja `send`/`connect` e `join` em index.html).

## APK
Com o site publicado, use https://www.pwabuilder.com e escolha Android.
