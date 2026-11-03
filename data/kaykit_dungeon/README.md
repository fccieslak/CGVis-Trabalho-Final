# KayKit Dungeon Remastered - assets da prova de importação

Esta pasta contém uma seleção pequena do pacote KayKit Dungeon Remastered 1.0,
usada para validar a leitura de modelos OBJ e do atlas de textura no projeto:

- `floor_tile_large`: piso modular;
- `wall`: parede;
- `chest`: baú;
- `torch_mounted`: tocha de parede;
- `dungeon_texture.png`: atlas referenciado pelos arquivos MTL.

## Origem e licença

- Criador: Kay Lousberg / KayKit.
- Repositório de origem: https://github.com/KayKit-Game-Assets/KayKit-Dungeon-Remastered-1.0
- Arquivos obtidos da revisão `b0ca9bd96a8072ab36a3a5464f00ed1e06a16d07`.
- Licença: CC0 1.0 Universal; cópia em `LICENSE.txt`.

## Teste

Compile o projeto e execute a partir de `bin/Linux`:

```sh
./main --dungeon-preview
```

Execute o comando no diretório `bin/Linux`. O modo opcional mostra piso,
três paredes, um baú e quatro tochas com o atlas do pacote. A iluminação usa
Phong com luz ambiente, difusa e especular; cada tocha contribui com uma luz
pontual quente. Sem `--dungeon-preview`, o exemplo gráfico original continua
sendo executado.

Os modelos do jogador e dos esqueletos ainda não estão incluídos: são recursos
de personagem separados e requerem uma escolha e validação próprias de formato.
