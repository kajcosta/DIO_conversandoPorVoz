
# Conversação por Voz Multilíngue com IA

Este projeto apresenta a implementação de um sistema de conversação por voz que integra **Speech-to-Text**, **Processamento de Linguagem Natural** e **Text-to-Speech**, mantendo a mesma lógica de funcionamento independentemente da tecnologia utilizada.

A proposta foca no **pensamento computacional**, na **organização da lógica** e na **replicação do mesmo problema em diferentes contextos e aplicações**.

## Estrutura do Desafio

Todo o projeto segue um fluxo lógico fixo, independente de variações técnicas ou bibliotecas utilizadas.

### Entrada

* Áudio contendo a pergunta do usuário em qualquer idioma suportado.

### Processamento

* Conversão do áudio em texto utilizando Whisper.
* Interpretação da pergunta pelo ChatGPT.
* Geração de uma resposta textual contextualizada.
* Conversão da resposta em áudio com Google Text-to-Speech.

### Saída

* Resposta final apresentada por voz ao usuário.

## Regra de Negócio

A regra central do sistema é única e não se altera:

* Toda interação começa por voz.
* O áudio é transcrito e, se necessário, traduzido.
* A resposta é sempre gerada por um modelo de linguagem.
* O retorno ao usuário ocorre por áudio.

Essa lógica é mantida independentemente da linguagem, biblioteca ou ambiente de execução.

## Pensamento Computacional Aplicado

Antes da implementação, o raciocínio lógico é sempre o mesmo:

1. Capturar o áudio do usuário
2. Converter áudio em texto
3. Interpretar a intenção da pergunta
4. Gerar uma resposta coerente
5. Converter texto em áudio
6. Retornar a resposta ao usuário

Esse fluxo não muda com a tecnologia utilizada, apenas a forma de implementação.


