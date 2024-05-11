# Pesquisa áudio

Projeto simples, feito com ajuda do [Gemini](https://gemini.google.com/?hl=pt-PT) na [Imersão Inteligência Artificial 2ª Edição da Alura](https://www.alura.com.br/imersao-ia-google-gemini), para fazer pesquisas, por trechos específicos, em arquivos de áudio (MP3) a partir da busca de palavras de suas transcrições. Em resumo, um áudio é carregado, transcrito e uma busca textual na transcrição informa em que posição no tempo do áudio, a palavra pesquisada se encontra (ou não).

## Requisitos

Para usar este projeto, você só precisa do [Google Colab](https://colab.research.google.com)
Caso queira testá-lo localmente, vai precisar de:

- [Jupyter Notebook](https://jupyter.org/install)
- [Python](https://www.python.org/downloads/) (recomendado: versão 3.6 ou superior)
- Bibliotecas Python: `moviepy`, `speech_recognition`, `pydub`

As dependências são instaladas via pip:

```bash
pip install moviepy speechrecognition pydub
```

## Como Usar

1. Baixe ou clone este repositório em sua máquina local.
2. Abra o Jupyter Notebook (`jupyter notebook`) e navegue até o diretório onde você salvou este projeto.
3. Abra o notebook `Transcricao_Audio_para_Legendas.ipynb`.
4. Execute as células do notebook, seguindo as instruções.

Certifique-se de ter um arquivo de áudio no formato MP3 disponível para transcrição de até 30 segundos de duração.

## Funcionalidades

- **Transcrição do áudio**: o notebook utiliza a biblioteca `speech_recognition` para transcrever o áudio fornecido em texto.
- **Geração das legendas**: com base na transcrição, o notebook gera legendas formatadas com o tempo de cada trecho de texto.
- **Pesquisa por trechos específicos**: o usuário faz a pesquisa, digitando palavras-chave e o notebook exibirá os trechos com os tempos correspondentes, caso encontre.

## Limitações (intencionais)

- **Duração do áudio**: apenas arquivos de até 30 segundos.
- **Formato de áudio**: apenas arquivos no formato MP3.

## Contribuições

Este projeto é apenas para estudo pessoal, um rascunho para uma futura aplicação. Fique a vontade para desenvolver a ideia em outras tecnologias (e me avise!)

## Licença

Licenciado sob a [GPL-3.0 License](LICENSE).
