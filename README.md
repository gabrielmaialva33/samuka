# Bar Samuka - Projeto de Som e Vídeo

Projeto de sistema de som e vídeo para o Bar Samuka, incluindo planta baixa, diagrama de conexões e esquema elétrico.

## Estrutura do Projeto

```
sakuma/
├── designs/          # Arquivos de design (.pen)
│   ├── samuka_1.pen  # Projeto completo (planta + diagramas)
│   ├── samuka.pen    # Layout inicial
│   └── layout_v2.pen # Versão alternativa
├── reference/        # Fotos dos equipamentos
│   ├── samsung_ht-z220t_back.jpg
│   ├── samsung_ht-z220t_ports.jpg
│   ├── goldship_subwoofer.jpg
│   └── goldship_connections.jpg
├── exports/          # Imagens exportadas dos designs
└── docs/             # Documentação adicional
```

## Equipamentos

| Equipamento | Modelo | Função |
|-------------|--------|--------|
| Home Theater | Samsung HT-Z220T | Receiver/DVD 5.1 - 70W |
| Subwoofer Ativo | Goldship 5.1 | Amplificador com controle de zonas |
| Caixas Auxiliares | - | 4 unidades (2 fundo + 2 frente) |
| Subwoofers | - | 2 unidades |
| Central | - | 1 unidade |
| Projetor | - | Vídeo para telão |

## Sistema de Som

### Conexões
```
Samsung HT-Z220T
      │
      │ RCA L/R
      ▼
Goldship Subwoofer 5.1
      │
      ├── FR → AUX Fundo Direita
      ├── FL → AUX Fundo Esquerda
      ├── RR → AUX Frente Direita
      ├── RL → AUX Frente Esquerda
      ├── CNT → Central
      └── SUB → Subwoofers
```

### Controle de Zonas
O Goldship permite controlar o volume de cada zona separadamente:
- **FRONT** - Volume das auxiliares do fundo (barracão)
- **REAR** - Volume das auxiliares da frente (área clientes)
- **WOOFER** - Volume dos subwoofers
- **CENTER** - Volume da central

## Layout do Bar

```
╔════════════════════════════════╗
║         BARRACÃO               ║
║    (Sala de TV / Copa)         ║
║  [AUX L]            [AUX R]    ║
║         [PROJETOR]             ║
║  [SUB]                         ║
╠════════════[TELÃO]═════════════╣
║ PASSAGEM                       ║
╠════════════════════════════════╣
║  [SUB]     BANHEIROS           ║
║  [AUX L]              [AUX R]  ║
║  [HT]  [CENTRAL]               ║
║          FRENTE                ║
╠═══════════[ENTRADA]════════════╣
╚════════════════════════════════╝
```

## Cores do Diagrama

| Cor | Código | Elemento |
|-----|--------|----------|
| Azul | #5c32d3 | Caixas Auxiliares |
| Roxo | #9610a0 | Subwoofers |
| Ciano | #28cccc | Central |
| Laranja | #ff6600 | Projetor |
| Preto | #1a1a1a | Telão |
| Verde | #2ca730 | Portas/Entradas |

## Arquivos de Design

Os arquivos `.pen` podem ser abertos com o [Pencil](https://pencil.elpassion.com/).

- **samuka_1.pen** - Projeto completo com:
  - Planta Baixa
  - Diagrama de Conexões
  - Legenda
  - Diagrama Elétrico Técnico

## Licença

Projeto pessoal - Bar Samuka
