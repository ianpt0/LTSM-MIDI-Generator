# LSTM MIDI Melody Generator

**Descrição:**
Este projeto demonstra a criação de um modelo de Machine Learning utilizando LSTM (Long Short-Term Memory) para gerar novas melodias MIDI com base em um conjunto de dados existente.

## Requisitos

- Python 3.x
- Bibliotecas Python: `numpy`, `music21`, `tensorflow`

Instale as dependências utilizando:

```bash
pip install numpy music21 tensorflow
```

## Utilização
1 - Escolha um Arquivo MIDI de Entrada:

Substitua './sample.mid' em midi_path no arquivo melody_generator.py pelo caminho do seu próprio arquivo MIDI.
Ajuste Parâmetros e Hiperparâmetros:

No arquivo melody_generator.py, ajuste os parâmetros conforme necessário, como o comprimento da sequência (sequence_length), o número de épocas (epochs), o tamanho do lote (batch_size), entre outros.
Execute o Código:

2 - Execute o código em um ambiente Python:

```bash
python melody_generator.py
Verifique os Resultados:
```

Após a execução, ouça a nova melodia gerada no arquivo 'output_generated.mid'.