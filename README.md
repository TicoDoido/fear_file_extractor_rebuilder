# Extrator e Recriador de Arquivos FEAR 1 PS3/XBOX360

Este projeto é uma ferramenta gráfica desenvolvida em Python para extrair e recriar arquivos de
container usados no jogo FEAR 1 para PS3 e XBOX360. A aplicação permite a extração de arquivos 
de container e a recriação do arquivo original mantendo o cabeçalho e aplicando a mesma compressão
usada nos arquivos originais.
Projeto focado apenas em aprendizado sobre estrutura de arquivos e compressão nos mesmos

## Funcionalidades

- Extração de arquivos de container (.cat, .matcat)
- Recriação de arquivos de container com cabeçalho original
- Aplicação de padding para múltiplos de 32 bytes (padrão do jogo)
- Compressão de arquivos ao recriar containers (zlib padrão)
- Interface gráfica intuitiva com Tkinter

## Requisitos

- Python 3.x
- Bibliotecas:
  - os
  - struct
  - zlib
  - tkinter
  - pillow (PIL)
