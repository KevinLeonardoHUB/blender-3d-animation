# Projeto de Animação 3D em Blender

Projeto completo de animação 3D desenvolvido em Blender, abrangendo modelação de cenário, materiais, rigging de personagem, animação, câmara, efeitos atmosféricos e design de som.

![Pré-visualização da cena no Blender](docs/process/01-camera-composition.png)

## Visão geral

O projeto acompanha uma personagem a deslocar-se por um ambiente natural estilizado. A cena combina elementos 3D personalizados e adaptados, árvores, rochas, relva, efeitos de céu, animação, movimentos de câmara e som.

O repositório documenta o resultado final e o processo de produção:

- modelação do ambiente e dos objetos;
- materiais, texturas e mapeamento UV;
- rigging da personagem e ajuste de pesos;
- animação de corrida e de objetos;
- composição da câmara;
- efeitos de vento, turbulência e céu;
- colocação de som e apresentação final.

## Resultado final

- [Ver no YouTube](https://www.youtube.com/watch?v=93E9mItYj8k)
- [`renders/final-animation.mp4`](renders/final-animation.mp4) — versão final combinada
- [`renders/first-sequence.mp4`](renders/first-sequence.mp4) — primeira sequência
- [`renders/second-sequence.mp4`](renders/second-sequence.mp4) — segunda sequência

## Estrutura do repositório

```text
blender-3d-animation/
├── src/
│   └── blender-animation.blend
├── renders/
│   ├── final-animation.mp4
│   ├── first-sequence.mp4
│   └── second-sequence.mp4
├── docs/
│   ├── presentation.pdf
│   ├── presentation.pptx
│   ├── ASSET_NOTES.md
│   └── process/
│       └── imagens selecionadas do desenvolvimento
├── .gitignore
├── README.md
└── README.pt.md
```

## Abrir o projeto

1. Clonar o repositório.
2. Abrir [`src/blender-animation.blend`](src/blender-animation.blend) no Blender.
3. Explorar a timeline, a câmara, o rig, os materiais e as coleções da cena.
4. Usar os renders finais como referência para o resultado pretendido.

O projeto foi desenvolvido com Blender 3.3.x. Versões mais recentes do Blender podem atualizar alguns dados quando o ficheiro for guardado.

## Recursos externos

Algumas texturas e ficheiros de áudio usados durante a produção vieram de fontes externas. Esses recursos não são redistribuídos neste repositório porque os respetivos termos de reutilização não foram verificados de forma independente. Consulte [`docs/ASSET_NOTES.md`](docs/ASSET_NOTES.md) para mais informações.

## Autor

**Quévin Leonardo Aguiar Tavares**

Este repositório é disponibilizado como projeto de portfólio. Não foi concedida uma licença para reutilização ou redistribuição.
