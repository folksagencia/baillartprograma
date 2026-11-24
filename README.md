# A mais Bela das Feras · Programa Baillart

Programa digital do espetáculo infantil da Baillart Academia de Dança (Teatro RioMar Fortaleza).
Site estático: um `index.html`, sem build.

## Publicar (GitHub + Vercel)
1. Crie um repositório no GitHub e envie **o conteúdo desta pasta** (o `index.html` precisa ficar na raiz).
2. Na Vercel: *Add New → Project → Import* o repositório.
3. Framework Preset: **Other**. Build Command e Output Directory: deixe em branco.
4. Deploy. Cada novo commit publica sozinho.

## O que falta preencher
- **Texto do espetáculo**: no `index.html`, procure `Falta só o texto.` e troque pelo texto final.
- **Fotos dos personagens**: salve em `img/personagens/` com os nomes abaixo (quadradas, ~800×800, .jpg).
  A foto aparece sozinha no quadro e o selo "Foto a enviar" some.

| Arquivo | Personagem |
|---|---|
| foto-01.jpg | Bela |
| foto-02.jpg | Fera |
| foto-03.jpg | Lumière e Orlosh |
| foto-04.jpg | Madame Samová e Zip |
| foto-05.jpg | Plumette |
| foto-06.jpg | Maestro e Guarda Roupa |
| foto-07.jpg | Cabideiro e Banqueta |
| foto-08.jpg | Feiticeira |
| foto-09.jpg | Gaston e Lefou |
| foto-10.jpg | Amigos de Gaston |
| foto-11.jpg | Moradores |
| foto-12.jpg | Crianças da vila |
| foto-13.jpg | Padeiro e bibliotecária |
| foto-14.jpg | Bimbetes |
| foto-15.jpg | Rosa vermelha |
| foto-16.jpg | Destaques ballet |
| foto-17.jpg | Destaques jazz |
| foto-18.jpg | Destaques sapateado |

## Prévia no WhatsApp
A capa da prévia é `img/og-capa.jpg` (1200×630). Título: **Baillart | A Mais Bela das Feras**.

O WhatsApp só lê a capa com o endereço completo. O `index.html` já aponta para `https://baillart-programa.vercel.app/`.
- Dê ao projeto na Vercel o nome **baillart-programa** e não precisa mudar nada; ou
- se o endereço for outro, troque `https://baillart-programa.vercel.app/` pelo seu nas linhas do topo do `index.html`.

O WhatsApp guarda a prévia em cache: teste o link pela primeira vez já com a capa no ar.

## Arquivos
- `img/og-capa.jpg` capa da prévia de link
- `img/` imagens do festival (nomes originais, convertidas para .jpg mais leve) e marcas
- `video/video_de_anuncio.mp4` vídeo da capa (720p, comprimido)
