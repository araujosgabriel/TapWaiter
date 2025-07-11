# TapWaiter

## Proposta Inicial

**TapWaiter** é um sistema de atendimento sem fio desenvolvido para bares, restaurantes e estabelecimentos similares. Sua principal função é permitir que os clientes chamem o atendente com apenas um toque em um botão disponível na mesa. O aviso é transmitido de forma instantânea e organizada para um módulo central na recepção, garantindo uma gestão eficaz dos pedidos.

---

## Problemática

Ambientes amplos, com alta rotatividade e número elevado de mesas, dificultam o atendimento rápido e eficaz. Garçons muitas vezes não conseguem visualizar todos os clientes no momento em que necessitam de algo, gerando insatisfação, espera prolongada e até perda de vendas. A sobrecarga da equipe, somada à ausência de um sistema de organização de chamados, compromete diretamente a qualidade do serviço.

---

## A Solução: TapWaiter

O TapWaiter surge como resposta a esse desafio, oferecendo uma solução minimalista, econômica e de fácil implementação. Cada mesa possui um pequeno dispositivo com botão e alimentação própria (duas pilhas AAA). Quando o cliente aciona o botão, o dispositivo envia um código único para a central, que imediatamente exibe a mesa chamada em uma fila organizada.

No lado do atendente, um módulo central recebe as chamadas e as organiza automaticamente em uma lista de espera exibida em um display, junto com notificações sonoras para facilitar a atenção.

---

## Proposta de Design
  ### Botão - Dispositivo de mesa
  <img src="../media/TapWaiter_conceptual_scheme.png" width="400px">
  
  _Esquema conceitual do dispositivo de mesa_
  
  <img src="../media/TapWaiter_Case_upper_view.png" width="400px">
  
  _Visão superior da case_
  
  <img src="../media/TapWaiter_Case_bottom_view.png" width="400px">
  
  _Visão inferior da case_

  ### 📐 Especificações Físicas

| Elemento           | Dimensão (mm)     |
|--------------------|-------------------|
| Largura da case    | 60 mm             |
| Comprimento da case| 60 mm             |
| Altura da case     | 35 mm             |
| Diâmetro do botão  | 16 mm             |




---

## Funcionamento

- Cada dispositivo de mesa (cliente) permanece em modo de baixo consumo, acordando apenas ao toque do botão.
- Ao ser pressionado, o botão ativa o microcontrolador e envia um código único para o servidor central.
- O servidor adiciona automaticamente o número da mesa à lista de espera e exibe no display.
- Um botão físico na central permite que o atendente remova o chamado atual e visualize o próximo.

---

## Benefícios

- Redução no tempo de atendimento
- Organização da ordem de chamados
- Aumento da satisfação do cliente
- Autonomia de meses com duas pilhas AAA
- Sistema escalável para mais de 50 mesas 
- Instalação simples e discreta, sem necessidade de rede Wi-Fi comercial

---

## 📩 Contato Comercial

Para demonstrações, orçamentos ou licenciamento comercial, entre em contato através de: [dev.gabrielaraujos@gmail.com]

---

> *Este projeto está em fase de desenvolvimento e testes em campo. Algumas informações internas foram propositalmente omitidas neste documento por se tratarem de lógica comercial protegida.*
