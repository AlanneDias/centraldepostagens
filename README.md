# Conteúdo e postagens · Alanne Dias Studio

Material para qualquer pessoa ou IA ajudar a criar e publicar posts do Studio Alanne Dias (identidade visual, sites e monogramas desenhados à mão). Leia este arquivo inteiro antes de postar.

- Site: https://alannedias.com (Monograma: /monograma/ · Orçamento: /orcamento/ · Portfólio: /portfolio/ · Sites: /site/)
- Behance: https://www.behance.net/alannedias
- Pinterest: alannediasdesigner
- Instagram e TikTok: @alannedias.designer
- WhatsApp: https://wa.me/5583998361156 (confira os dígitos: 55 83 99836-1156)

## O que tem aqui

| Pasta ou arquivo | Conteúdo |
|---|---|
| `dados/projetos.json` | 17 projetos (8 sites, 7 identidades visuais, 2 de monograma). Para cada projeto e cada rede: guia de postagem, textos em português e inglês, hashtags, palavras-chave e quais mídias usar. |
| `dados/hashtags.json` | Hashtags gerais por tipo (site, idv, mono), em PT e EN. |
| `dados/behance-projetos.json` | Projetos do Behance com descrição, tags e links diretos das imagens (servem de `image_url` para Pins). |
| `dados/pinterest-pastas.json` | IDs das pastas do Pinterest. |
| `dados/pins-publicados.csv` | Registro do que já foi postado. **Acrescente uma linha a cada Pin novo.** |
| `dados/desempenho-pinterest-90d.md` | O que funciona e o que não funciona no Pinterest, com números. |
| `midia/sites/` | Para cada site: `-story` (9:16), `-feed` (4:5), `-pin` (2:3) e `-shot` (4:3), em `.mp4` (o site sendo usado, com interação) e `.jpg`. |
| `midia/identidade-e-monogramas/` | Capas e vídeos verticais dos projetos de identidade visual e monograma. |
| `midia/carrosseis/` | Imagens 4:5 dos carrosséis, na ordem (`-01`, `-02`...). A capa é o `-feed.jpg` do projeto. |

Códigos dos projetos: `bibilica`, `renata`, `evy`, `unora`, `salm`, `luana`, `natalia`, `legacy` (sites) · `thais`, `dayana`, `poli`, `etax`, `salmidv`, `bibidv`, `marcas` (identidade visual) · `monotat`, `monocas` (monogramas).

## Regras de estilo (decididas pela Alanne)

1. **A identidade do cliente em destaque.** Fundo e cores da marca do cliente, nada de base escura do Studio.
2. **Pouca propaganda.** No máximo um crédito pequeno "alannedias.com". Sem títulos grandes nem botão de orçamento na arte.
3. **Nos sites, mostrar a interação.** O diferencial é o site sendo usado: arrastar o vestido até a cesta (Bibilica), montar o bem-casado (Renata), arara de looks (EVY), formulário de agendamento (UNORA).
4. **Textos em português e inglês.** O inglês vale para Dribbble e galerias; o português, para Instagram, Facebook e TikTok.

## Regras do Pinterest (baseadas nos dados)

1. **Sempre título com palavra-chave + projeto**, por exemplo "Identidade Visual para Corretora de Imóveis | Papelaria Preto e Dourado". Pin sem título quase não gera clique.
2. **Descrição de 2 a 3 frases** explicando o trabalho, com 4 ou 5 hashtags no fim, e **texto alternativo** sempre preenchido.
3. **Link que vende, nunca o Instagram.** Monograma → `https://alannedias.com/monograma/`. Identidade visual → o projeto no Behance ou `/portfolio/`. Site → `/site/` ou `/orcamento/`. Use UTM: `?utm_source=pinterest&utm_medium=social&utm_campaign=<codigo>`.
4. **Oferta quando houver:** preço ou prazo no título ("a partir de R$ 490", "pronto em 3 dias") aumenta muito o clique.
5. **Constância:** 1 a 3 Pins por dia, misturando sites, identidade visual e monogramas. Não repita uma imagem já postada: confira o `pins-publicados.csv`.
6. **Pastas:** identidade visual → "Identidade Visual" · monograma de casamento → "Monograma de Casamento" · tatuagem → "tattoos" · sites → "Portfolio".

## Como publicar

- **Pinterest:** pela integração Windsor.ai (conector `pinterest_organic`, ação `create_pin`, conta `alannediasdesigner`). A imagem precisa de um endereço público, por exemplo do Behance (`mir-s3-cdn-cf.behance.net/project_modules/1400/...`) ou do site (`alannedias.com/img/...`). O Windsor no plano gratuito aceita uma conta conectada por vez.
- **Instagram, Facebook, TikTok, LinkedIn, Threads, Dribbble e Behance:** publicação manual. Os textos e as mídias estão em `dados/projetos.json` e `midia/`.
- **Central de Postagens** (página com botões de copiar e baixar): https://claude.ai/artifact/A8qhZPCV9A8771288PTyAm (acesso só da Alanne).

## Antes de afirmar algo sobre um cliente

Descrições de projetos foram escritas a partir dos sites e do Behance. Na dúvida sobre segmento ou nome, confira no projeto do Behance (ex.: Dayana Silveira aparece como "Makeup" no portfólio e como "Odontologia" no Behance).
