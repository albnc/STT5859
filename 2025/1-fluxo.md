---
title: "Teoria de fluxo de Tráfego"
subtitle: "STT5859.2025"
author: "Prof. André Luiz Cunha"

number_sections: true
---

**TÓPICOS**

  - [ ] Diagrama espaço-tempo em vias urbanas
  - [ ] Caracterização do tráfego (parâmetros do tráfego)
  - [ ] Modelos macroscópicos (Greenshields e outros)
  - [ ] Ondas de choque


# Introdução

- Modelo de locomoção veicular:
    - movimento de um único veículo
    - sem interação com demais veículos
    
- Modelo de corrente de tráfego:
    - uso simultâneo da via por diversos veículos
    - interação entre veículos
    
# Modelagem da corrente de tráfego

- Correntes com fluxo **ininterrupto**
    - sem semáforo ou sinais de PARE e DÊ A PREFERÊNCIA
    - rodovias e vias expressas
    
- Correntes com fluxo **interrompido**
    - controlados por PARE ou semáforo
    - vias arteriais urbanas, coletoras e locais
    
## Parâmetros das correntes de tráfego

- Diagrama Espaço-tempo (ferramenta essencial em Engenharia de Transportes)

- Parâmetros:

| **Microscópico** | **Macroscópico** |
| :--------------- | :--------------- |
| headway [s/veic] | fluxo [veic/h]   |
| tempo de viagem [s/m] | velocidade [km/h]   |
| espaçamento [m/veic] | densidade [veic/km]   |



- Exemplos:

  - Tese doutorado [Cunha, 2013] (imagens da apresentação)
  - Vídeo da dissertação do Leandro (2017)
  - Vídeo de coleta automática com Computer Vision


### Fluxo de tráfego (*q*)

$$q = \frac{n}{t}$$

- $q$: fluxo de tráfego, em veic/unidade de tempo;
- $n$: número de veículos observados por um certo ponto da via, durante um intervalo de tempo $t$;
- $t$: duração do intervalo de tempo.


Sabe-se que:

$$t = \sum_{i=1}^{n}  h_i$$

- $h_i$: *headway*, intervalo de tempo entre a passagem do (*i* - 1) e do *i*-ésimo veículos

Portanto:

$$q = \frac{n}{\sum_{i=1}^{n}  h_i} \Rightarrow q = \frac{1}{\overline{h}}$$


### Velocidade da corrente de tráfego (*u*)

1. **Velocidade média no tempo (média aritmética das velocidades)**

$$\overline{u_t} = \frac{\sum_{i=1}^{n} u_i}{n}$$

- $\overline{u_t}$: velocidade média no tempo, em km/h;
- $u_i$: velocidade do *i*-ésimo veículo, em km/h;
- $n$: número de veículos observados.

2. **Velocidade média no espaço (média harmônica das velocidades)**

$$\overline{u_s} = \frac{l}{\overline{t}}$$

- $\overline{u_s}$: velocidade média no espaço, em km/h;
- $l$: comprimento do trecho percorrido;
- $\overline{t}$: tempo médio para percorrer o trecho.

Portanto, 

$$\overline{t} = \frac{1}{n} \sum_{i=1}{n} t_i$$



### Densidade de tráfego (*k*)


$$k = \frac{n}{l}$$

- $k$: densidade, em veic/unidade de comprimento;
- $n$: número de veículos que ocupam certo trecho da via, num certo instante de tempo;
- $l$: comprimento do trecho, em unidade de comprimento.

Portanto, 

$$\overline{l} = \sum_{i=1}{n} s_i$$

- $s_i$: espaçamento, distância entre o (*i*-1) e o *i*-ésimo veículos, medida com mesma referência (para-choque ou eixo dianteiro).


# Modelos Macroscópicos

## Relação fundamental

$$q = k \cdot u$$

$$FLUXO = DENSIDADE \cdot VELOCIDADE$$

$$\frac{VEIC}{H} = \frac{VEIC}{KM} \cdot \frac{KM}{H}$$


## Modelo de Greenshields (1935)

### Equação

### Relação entre parâmetros macroscópicos

## Outros Modelos

- Pipes
- Van Aerde (1995)
- 

# Ondas de choque

<https://youtu.be/goVjVVaLe10?si=-vaVF6cG4vcxma2S>

Imagem da Formação de pelotão em rodovias
Imagem de fila de semáforo em Elefteriadou



# Referências

"Principles of Highway Engineering and Traffic Analysis" (cap.5, Mannering & Washburn) - Fundamentals of Traffic flow and Queuing Theory
<!--"Traffic Stream Models" (cap.3 Papacostas & Prevedouros) - Shock Waves in Traffic
"Mathematical and empirical models" (cap.6, Elefteriadou) - Shockwave analysis
-->



  
