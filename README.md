# Pesquisa áudio

Projeto simples, feito com ajuda do [Gemini](https://gemini.google.com/?hl=pt-PT) na [Imersão Inteligência Artificial 2ª Edição da Alura](https://www.alura.com.br/imersao-ia-google-gemini) para pesquisa em arquivos de áudio no formato MP3 a partir da busca de palavras de suas transcrições. Em resumo, um arquivo de áudio é carregado, transcrito e uma busca textual na transcrição informa em que tempo do áudio a palavra pesquisada está presente (ou não).

## Requisitos

Para usar este projeto, você só precisará do [Google Colab](https://colab.research.google.com)
Caso opte localmente, você precisará de:

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

Certifique-se de ter um arquivo de áudio no formato MP3 disponível para transcrição. O projeto foi projetado para arquivos de áudio de até 30 segundos de duração.

## Funcionalidades

- **Transcrição de Áudio**: O notebook utiliza a biblioteca `speech_recognition` para transcrever o áudio fornecido em texto.
- **Geração de Legendas**: Com base na transcrição do áudio, o notebook gera legendas formatadas com tempo.
- **Pesquisa por Trechos de Áudio**: O usuário pode pesquisar trechos específicos do áudio digitando palavras-chave. O notebook exibirá os trechos correspondentes.

## Limitações (intencionais)

- **Duração do Áudio**: O projeto suporta apenas arquivos de áudio de até 30 segundos.
- **Formato de Áudio**: Atualmente, apenas arquivos de áudio no formato MP3 são suportados.

## Contribuições

Projeto para fins de estudo pessoal.

## Licença

Licenciado sob a [GPL-3.0 License](LICENSE).
