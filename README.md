# Omarchy Theme — Brasil
Tema do Omarchy inspirado no Brasil: paleta verde/amarelo/azul moderna, e 83 wallpapers em três categorias, uma para cada uma das 27 unidades federativas mais o conjunto nacional:
- **Foto** — uma paisagem ou marco real de cada estado (cidade e local identificados)
- **Bandeira** — a bandeira oficial de cada estado
- **Mapa** — a localização de cada estado dentro do Brasil

Todo wallpaper traz uma legenda gravada na própria imagem, no canto inferior esquerdo, identificando o estado e, no caso das fotos, o local e a cidade retratados.

## Aplicar o tema

```bash
omarchy theme set brasil
omarchy theme bg next   # alterna entre os 83 wallpapers
```

## Wallpapers por estado

| UF | Estado | Região | Foto (local / cidade) |
|----|--------|--------|------------------------|
| AC | Acre | Norte | Palácio Rio Branco — Rio Branco |
| AL | Alagoas | Nordeste | Praias de Maragogi — Maragogi |
| AM | Amazonas | Norte | Teatro Amazonas — Manaus |
| AP | Amapá | Norte | Marco Zero do Equador — Macapá |
| BA | Bahia | Nordeste | Farol da Barra — Salvador |
| CE | Ceará | Nordeste | Jericoacoara — Jijoca de Jericoacoara |
| DF | Distrito Federal | Centro-Oeste | Congresso Nacional — Brasília |
| ES | Espírito Santo | Sudeste | Convento da Penha — Vila Velha |
| GO | Goiás | Centro-Oeste | Chapada dos Veadeiros — Alto Paraíso de Goiás |
| MA | Maranhão | Nordeste | Lençóis Maranhenses — Barreirinhas |
| MG | Minas Gerais | Sudeste | Cânion de Furnas — Capitólio |
| MS | Mato Grosso do Sul | Centro-Oeste | Gruta do Lago Azul — Bonito |
| MT | Mato Grosso | Centro-Oeste | Pantanal Mato-grossense — Poconé |
| PA | Pará | Norte | Mercado Ver-o-Peso — Belém |
| PB | Paraíba | Nordeste | Praia de Cabo Branco — João Pessoa |
| PE | Pernambuco | Nordeste | Arquipélago de Fernando de Noronha — Fernando de Noronha |
| PI | Piauí | Nordeste | Serra da Capivara — São Raimundo Nonato |
| PR | Paraná | Sul | Cataratas do Iguaçu — Foz do Iguaçu |
| RJ | Rio de Janeiro | Sudeste | Cristo Redentor — Rio de Janeiro |
| RN | Rio Grande do Norte | Nordeste | Dunas de Genipabu — Extremoz |
| RO | Rondônia | Norte | Rio Madeira — Porto Velho |
| RR | Roraima | Norte | Monte Roraima — Uiramutã |
| RS | Rio Grande do Sul | Sul | Vale dos Vinhedos — Bento Gonçalves |
| SC | Santa Catarina | Sul | Ponte Hercílio Luz — Florianópolis |
| SE | Sergipe | Nordeste | Cânion do Xingó — Canindé de São Francisco |
| SP | São Paulo | Sudeste | MASP — São Paulo |
| TO | Tocantins | Norte | Cachoeira da Velha — Mateiros |

Mais o conjunto **Nacional**: bandeira do Brasil e mapa político das 27 unidades federativas.

## Fontes das imagens

- **Bandeiras**: arquivo oficial referenciado no infobox de cada estado na Wikipédia (campo `image_flag`), obtido via Wikimedia Commons.
- **Mapas**: mapa de localização de cada estado (campo `image_map` do infobox) e o mapa político nacional rotulado, ambos via Wikimedia Commons.
- **Fotos**: fotografias reais dos locais listados acima, licenciadas para reuso.

Estrutura completa fica registrada em [`wallpapers.json`](wallpapers.json), listando estado, região, tipo, local/cidade (quando aplicável) e fonte de cada arquivo em `backgrounds/`.
