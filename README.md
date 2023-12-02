![logohotel](https://github.com/GabrielJordaoM/projeto-hotel/assets/69699073/4c2704f2-4163-4ef5-be51-d587137d24b5)

# Hotel Maresia - Projeto final 
Experimente o luxo à beira-mar no Hotel Maresia. Quartos elegantes com vistas deslumbrantes, restaurante à beira-mar "Sabor do Mar" e piscina infinita. Explore a natureza local com nosso guia personalizado ou relaxe no spa Maresia. Uma experiência única de tranquilidade e sofisticação. _Bem-vindo ao seu refúgio à beira-mar._

##O projeto
O projeto final de Linguagem de Programação do curso de Análise e Desenvolvimento de sistemas (ADS) - 2º Semestre - Noite se consiste na criação de dois diferentes sistemas para manejamento de partes do hotel ficticio chamado "hotel Maresia". Onde foram criados o sistema de manejamento de estoque de produtos do hotel e o sistema de reservas de quartos do hotel. 

##Indice

## Status do projeto 
  ### ✔️ Projeto pronto para entrega [02/12/23]
  ### ❗  Troubleshooting de integração de sistemas [01/12/23]

## Por que usar C :

A linguagem de programação C é escolhida por diversos motivos, sua eficiência e desempenho notáveis a tornam ideal para o desenvolvimento de software rápido e de baixo nível. A sintaxe simples facilita a aprendizagem, enquanto sua portabilidade permite a execução em diferentes sistemas. A linguagem C é amplamente utilizada em sistemas embarcados devido à sua proximidade com o hardware além de sua flexibilidade, proporcionando controle direto sobre a memória que a torna valiosa para programadores que buscam equilíbrio entre abstração e controle. _Em resumo, C é uma escolha versátil, combinando eficiência, simplicidade e flexibilidade._

## Instalação para utilizar o executavel 
O projeto necessita de um compilador MinGW para execução correta, o link abaixo mostra passo a passo a instalação
  >https://www.youtube.com/watch?v=sXW2VLrQ3Bs

![checkinn](https://github.com/GabrielJordaoM/projeto-hotel/assets/69699073/c288e1bc-5d52-47cc-ad85-23c4458d3154)

# Check-Inn - Sistema de Reservas de Hotel
O projeto denominado _Checkinn_ é um sistema de manejamento de reservas de hotel. 

O sistema permite que o usuário visualize os quartos disponiveis, reserve quartos e realize check-in e check-out de suas reservas. 

# Inicio do programa

## 🔨 Funcionalidades 
### 1 - Visualizar Quartos :
Primeira opção a aparecer no menu, nela você poderá fazer sua reserva após digitar o número do quarto, seu nome e a quantidade de dias.
  >Visualização (print)

### 2 - Reservar Quarto :
Segunda opção a aparecer no menu, faz a reserva de um quarto ainda não ocupado. 
  >Escolha um quarto vago
  >>Digite o nome
  >>>Digite a quantidade de dias
  >>>>Mensagem de confirmação de reserva

Mensagens de erro de cadastro 
  >Quarto fora dos parametros
  >>Nome invalido
  >>>Dias invalidos

### 3 - Realizar check-in :
Terceira opção a aparecer no menu, cria um check-in de um quarto já reservado. 
  >Digite o numero do quarto
  >>Mensagem de confirmação de reserva

Mensagens de erro de check-in
  >Quarto não reservado 

### 4 - Realizar check-out :
Quarta opção a aparecer no menu, faz o check-out do quarto utilizado e o libera na visualização de quartos. 
  >Digite o numero do quarto
  >>Mensagem de confirmação de check-out

Mensagens de erro de check-in
  >Não da para dar check-out em um quarto que não tenha check-in
  >Não da para dar check-out em um quarto não reservado

### 5 - Sair
A ultima opção do menu, use esta opção quando quiser encerrar suas ações dentro do programa.
