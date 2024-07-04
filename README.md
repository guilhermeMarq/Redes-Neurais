<p align="center">
  <img width="250px" src="https://github.com/guilhermeMarq/Metodos_Numericos/assets/72332375/f66138d1-befd-4cdf-9842-4a52d5fcf290" alt="Logo 2">
</p>

# Physics-Informed Neural Networks (PINNs)

Este projeto é uma implementação em Python de Redes Neurais Informadas pela Física (PINNs), destinada a resolver três problemas distintos de engenharia e física. O programa é destinado a modelar sistemas fisicos através de equações diferenciais, condições iniciais e condições de contorno que governam o fenômeno físico estudado.

## Problemas Abordados
1. **Sistema Massa-Mola-Amortecedor**
2. **Deformação de Material Heterogêneo**
3. **Difusão de Calor**

### 1. Sistema Massa-Mola-Amortecedor
O primeiro problema visa modelar um sistema de vibração livre de um grau de liberdade com amortecimento viscoso. A equação do movimento que descreve o comportamento dinâmico do sistema é dada por:
$$m \frac{d^2 x}{dt^2} + \mu \frac{dx}{dt} + kx = 0$$
![ezgif com-added-text](https://github.com/guilhermeMarq/Redes_Neurais/assets/72332375/0a6edc97-4654-4209-93e4-f9840ae2871a)

### 2. Deformação de uma barra heterogênea
O segundo problema consiste em determina a deformação $u$ ao longo de uma barra elástica de comprimento $L$ composta por dois materiais diferentes, com módulo de elasticidade $E_1$ e $E_2$, respectivamente, e comprimentos $L_1$ e $L_2$. A equação geral de equilíbrio de forças em um corpo elástico submetido a um carregamento axial unidimensional na direção $x$ com modolu de elasticidade variavel pode ser expressa como:
$$\frac{d}{dx}\left[E(x)\frac{du}{dx}\right] = 0$$

$$
E(x) = \begin{cases}
E_1 & \text{para } 0 \leq x \leq L_1 \\
E_2 & \text{para } L_1 \leq x \leq L
\end{cases}
$$

### 3. Difusão de Calor
O terceiro problema tem como objetivo modelar a distribuição de temperatura em um sistema com transferência de calor unidimensional para coordenadas cartesianas, em regime transiente e sem geração de calor. A equação diferencial parcial que descreve esse sistema é igual a:
$$k \frac{\partial^2 T}{\partial x^2} = \rho c_p \frac{\partial T}{\partial t}$$

![Grafico 3d - Soluçao Analitica](https://github.com/guilhermeMarq/Redes_Neurais/assets/72332375/c71a7788-a367-4382-bf78-37dbff8a25b7)


## Requisitos:

* Python 3.10 + 


## Instalação

Clone ou faça o download deste repositório.


## Contribuindo

Todas as contribuições, reporte de bugs, correções, melhorias na documentação, aprimoramentos e ideias são bem-vindos.

"*Os erros são os portais da descoberta.*" 
                                             -**James Joyce**

## Licença

Este programa é distribuído sob a licença MIT, isto é, o programa não tem restrições para o uso, modificação ou distribuição. Consulte o arquivo `LICENSE` para obter mais informações.er mais informações.
