<p align="center">
    <img width="300px" src=".github/assets/logo_2.png">
</p>

<p align="center">
<a href="https://dio.me/"><img src="https://img.shields.io/badge/DIO-Project-FED564?logo=youtube" alt="DIO - Project"></a>
<a href="https://www.gnu.org/software/bash/" title="Go to Bash homepage"><img src="https://img.shields.io/badge/Prompt-Project-FED564?logo=gnu-bash&amp;logoColor=white" alt="Made with Bash"></a>
<a href="https://aws.amazon.com/" title="Powered by AWS">
  <img src="https://img.shields.io/badge/Powered%20by-AWS-FED564?logo=icloud&logoColor=white" alt="Powered by AWS">
</a>
</p>

<p align="center">
  <h3 align="center">🏋️‍♂️ Assistente de Personal Trainer - Gerador de Treino Ideal</h3>
Este projeto é um desafio de Prompt Engineer, onde o objetivo é criar um prompt que ajuda a montar o treino ideal para cada combinação de fatores, como biotipo corporal, disponibilidade de tempo e tipo de exercícios preferidos. O assistente de personal trainer gerado por esse prompt será capaz de personalizar os treinos de acordo com as características e necessidades do usuário.
O projeto deve ser feito utilizando as boas práticas de prompt engineer.
</p>

## 📋 Índice

- [📋 Índice](#-índice)
- [📝 Introdução](#-introdução)
- [💪 Biotipos Corporais](#-biotipos-corporais)
- [📅 Dias Disponíveis para Treino](#-dias-disponíveis-para-treino)
- [🏋️ Tipos de Exercícios](#️-tipos-de-exercícios)
- [🥕 Nutrição](#-Nutrição)
- [👨‍🏭 Trabalho](#-Trabalho)
- [🛠️ Regras de negócio](#️-regras-de-negócio)
- [🎯 Prompt de Resposta Proposto](#-prompt-de-resposta-proposto)

---

## 📝 Introdução

Este projeto visa criar um assistente de personal trainer automatizado que ajuda a gerar treinos personalizados. O usuário fornecerá informações como o biotipo corporal, a quantidade de dias disponíveis para treinar na semana e o tipo de exercício preferido, e o assistente gerará um plano de treino ideal com base nessas informações.

---
## Areas de Variáveis
   - biotipo = endomorph
   - periodização = 3 dias de treino
   - tipo = HIIT e Cardio
   - nutrição = Mix
   - trabalho = Trabalho Online
---

## 💪 Biotipos Corporais

A primeira regra para personalizar o treino é determinar o biotipo corporal do usuário. Existem três biotipos principais:

<table>
  <tr>
    <th>Imagem</th>
    <th>Biotipo</th>
    <th>Descrição</th>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/ectomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Ectomorfo</strong></td>
    <td>Corpo mais magro, difícil ganhar peso e massa muscular.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/mesomorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Mesomorfo</strong></td>
    <td>Corpo naturalmente musculoso, facilidade para ganhar massa muscular e perder gordura.</td>
  </tr>
  <tr>
    <td style="text-align: center;">
      <img src=".github/assets/endmorph.jpg" width="50%" height="50%">
    </td>
    <td><strong>Endomorfo</strong></td>
    <td>Corpo com tendência a acumular gordura, maior dificuldade em perder peso.</td>
  </tr>
</table>

> **Nota:** Escolha o biotipo que mais se aproxima do seu corpo atual para que o treino seja mais eficiente.

---

## 📅 Dias Disponíveis para Treino

A segunda regra é determinar quantos dias por semana o usuário tem disponível para treinar. Dependendo do número de dias, o treino sugerido pode variar:

| **Imagem**                                                     | **Dias por Semana** | **Tipo de Treino Sugerido** |
| -------------------------------------------------------------- | ------------------- | --------------------------- |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 1 dia               | Treino Full Body            |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 3 dias              | Treino ABC                  |
| <img src=".github/assets/calendar.png" width="50" height="50"> | 5 dias              | Treino ABCDE                |

- **Full Body**: Treino que trabalha o corpo todo em uma única sessão.
- **ABC**: Divisão do treino em três dias, cada um focado em grupos musculares diferentes.
- **ABCDE**: Divisão do treino em cinco dias, com foco ainda mais específico em cada grupo muscular.

---

## 🏋️ Tipos de Exercícios

A terceira regra envolve a escolha do tipo de exercício preferido. Aqui estão algumas categorias com exemplos:

| **Imagem**                                                       | **Tipo de Treino** | **Descrição**                                                                                                 |
| ---------------------------------------------------------------- | ------------------ | ------------------------------------------------------------------------------------------------------------- |
| <img src=".github/assets/dumbells.png" width="50%" height="50%"> | **Funcional**      | Exercícios que melhoram a funcionalidade do corpo, usando movimentos naturais.                                |
| <img src=".github/assets/4760665.png" width="50%" height="50%">  | **Maquinário**     | Exercícios feitos em máquinas, com foco em isolar grupos musculares.                                          |
| <img src=".github/assets/barr.png" width="50%" height="50%">     | **Peso Livre**     | Exercícios com pesos livres, como halteres e barras, para trabalhar vários grupos musculares simultaneamente. |
| <img src=".github/assets/cardio.png" width="50%" height="50%">   | **Cardio**         | Exercícios voltados para melhorar a resistência cardiovascular, como corrida ou ciclismo.                     |
| <img src=".github/assets/hiit.png" width="50%" height="50%">     | **HIIT**           | Treinos intervalados de alta intensidade, ótimos para queima de gordura.                                      |

---

## 🥕 Nutrição

 A quarta regra envolve a escolha da dieta preferida. Aqui estão algumas categorias com exemplos:
- Fitness: Dieta com Muitas Proteínas (Frango, Ovos, Iogurte, Lentilhas), Verduras e Frutas
- Mix: Mistura de Comidas com Proteínas e Carboidrato, mas leve no açúcar
- Lazy: Comida de Fast Food "Fitness". Popeyes, Subway, Olive Garden, etc. (Muito Carboidrato)
---

## 👨‍🏭 Trabalho

 A quinta regra envolve a escolha do Trabalho atual
- Trabalhos Físicos: Trabalhos que demanda muita energia, treinamento, e/ou de costume. (Sports, Treinador Personal, etc.)
- Trabalhos Mixed: Trabalhos que demanda planejamento, foco, e/ou estrategia. (Líder Militar, Cinematografia, Grand Master Xadrez, etc.)
- Trabalhos Estudo: Trabalhos que demanda o uso total do cerebro para estudo e/ou não falhar. (Doutor/a, Cirurgião, etc.)
- Trabalho Online: Trabalho que demanda nenhum uso do corpo físico. (Programador, Escritor, Dublador, etc.)
---

## 🛠️ Regras de negócio

1. **Identifique seu biotipo corporal** consultando a seção de biotipos.
2. **Determine quantos dias por semana você pode treinar** e escolha o tipo de treino mais adequado.
3. **Selecione o tipo de exercício** que prefere realizar e que se encaixa melhor nos seus objetivos.
4. Use o prompt do assistente para gerar um plano de treino personalizado.

---
# Prompts

## ❓ O Prompt
[...]

Baseado nas regras acima, examine minhas preferencias na Areas de Variáveis e crie um plano de treinamento para mim.

## 🎯 Prompt de Resposta Proposto

Claro! Vamos criar um plano de treinamento baseado nas suas preferências e informações fornecidas:

### **Plano de Treino Personalizado**

**Biotipo:** Endomorfo  
**Periodização:** 3 dias de treino por semana  
**Tipo de Exercício:** HIIT e Cardio  
**Nutrição:** Mix  
**Trabalho:** Trabalho Online

#### **Estrutura do Treino ABC**

Com base no seu biotipo e no fato de que você tem 3 dias por semana para treinar, o plano se concentra em HIIT e Cardio para maximizar a queima de gordura e melhorar a resistência cardiovascular. Aqui está a divisão dos treinos:

---

**Dia A - Cardio e Core**

- **Aquecimento:**
  - 5-10 minutos de caminhada rápida ou corrida leve

- **Cardio:**
  - Corrida Intervalada: 30 minutos (1 minuto de corrida intensa seguido por 2 minutos de caminhada)

- **Exercícios de Core:**
  - Prancha: 3 séries de 30-45 segundos
  - Crunches: 3 séries de 15-20 repetições
  - Elevação de Pernas: 3 séries de 15-20 repetições

- **Alongamento:**
  - 5-10 minutos de alongamentos focados em abdômen e quadris

---

**Dia B - HIIT**

- **Aquecimento:**
  - 5-10 minutos de pular corda ou bicicleta

- **Treino HIIT:**
  - Circuito de 4 Rodadas:
    - 30 segundos de Burpees
    - 30 segundos de Saltos no Lugar
    - 30 segundos de Mountain Climbers
    - 30 segundos de Descanso

- **Alongamento:**
  - 5-10 minutos de alongamentos dinâmicos e estáticos

---

**Dia C - Cardio Moderado e Corpo Superior**

- **Aquecimento:**
  - 5-10 minutos de caminhada rápida ou bicicleta

- **Cardio:**
  - Ciclismo ou Elíptico: 30 minutos em intensidade moderada

- **Exercícios de Corpo Superior:**
  - Flexões: 3 séries de 10-15 repetições
  - Remada com Halteres: 3 séries de 10-12 repetições
  - Desenvolvimento de Ombros com Halteres: 3 séries de 10-12 repetições

- **Alongamento:**
  - 5-10 minutos de alongamentos focados em peito, costas e ombros

---

### **Notas Adicionais**

- **Aquecimento e Alongamento:** Sempre inicie com um aquecimento leve e finalize com alongamentos para prevenir lesões e melhorar a flexibilidade.
- **Recuperação:** Com o seu biotipo endomorfo, é importante incluir dias de descanso e garantir uma boa recuperação entre os treinos. Atividades leves, como caminhadas, podem ser benéficas nos dias sem treino.
- **Nutrição:** Para um biotipo endomorfo e considerando que você tem um trabalho online, uma dieta balanceada é crucial. Mantenha uma mistura de proteínas e carboidratos, evitando excessos de açúcares e priorizando alimentos integrais.

#### **Exemplos de Refeições para uma Dieta Mix**

- **Café da Manhã:** Aveia com frutas e uma fonte de proteína, como iogurte grego ou ovo cozido.
- **Almoço:** Peito de frango grelhado com arroz integral e vegetais variados.
- **Jantar:** Salada de quinoa com legumes e tofu ou peixe grelhado.

- **Lanches:** Frutas frescas, nozes ou um shake de proteína.

---

Este plano de treino e nutrição deve ajudar a atingir seus objetivos de forma eficaz. Se precisar de mais ajustes ou tiver alguma dúvida, estou à disposição para ajudar!
