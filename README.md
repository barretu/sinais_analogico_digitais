# 📡 Sinais Analógico & Digital

Visualização interativa para entender a diferença entre sinais analógicos e digitais, e como o **sample rate** influencia na qualidade da conversão.

🔗 **[Acesse aqui](https://barretu.github.io/sinais_analogico_digitais/)**

---

## O que você vai aprender

- A diferença entre sinais **analógicos** (contínuos) e **digitais** (discretos)
- O que é **amostragem** — o processo de converter um sinal analógico em digital
- O que é **sample rate** — a taxa que define quantas amostras são coletadas por segundo
- Como o sample rate baixo causa **aliasing** (distorção do sinal original)
- O **Teorema de Nyquist** na prática: por que o sample rate precisa ser pelo menos o dobro da frequência do sinal

---

## Como usar

Abra o site e **arraste o slider** de Sample Rate para a esquerda e para a direita.

- ⬅️ **Poucos samples** — o sinal digital (linha vermelha) se distancia bastante da onda original
- ➡️ **Muitos samples** — o sinal digital se aproxima cada vez mais do analógico
- 🟡 Os **pontos amarelos** são as amostras coletadas em cada instante

---

## Conceitos abordados

### Sinal Analógico
Sinal contínuo que pode assumir infinitos valores ao longo do tempo. Representa diretamente o fenômeno físico (som, luz, temperatura).

### Sinal Digital
Representação discreta do sinal, codificada em bits (0 e 1). Não imita o fenômeno — descreve numericamente.

### Amostragem
Processo completo de medir o sinal analógico em instantes específicos no tempo e converter cada medição em um valor digital.

### Sample Rate
Parâmetro numérico que define quantas amostras são coletadas por segundo (Hz). Exemplos reais:

| Aplicação | Sample Rate |
|---|---|
| Telefonia | 8.000 Hz |
| CD de áudio | 44.100 Hz |
| Áudio profissional | 96.000 Hz |

### Aliasing
Distorção que ocorre quando o sample rate é baixo demais — o sinal reconstruído não representa mais o original.

### Teorema de Nyquist
Para reconstruir um sinal com fidelidade, o sample rate precisa ser **pelo menos o dobro** da maior frequência presente no sinal.

---

## Tecnologias

- HTML5 + CSS3 + JavaScript puro
- Canvas API para renderização do gráfico
- Design responsivo — funciona no celular e no desktop

---

*Desenvolvido como material de apoio para a disciplina de Sistemas Digitais.*
