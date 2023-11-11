---
title: Informações Gerais do Servidor
description: 
published: true
date: 2023-11-11T18:52:49.580Z
tags: tibia mmorpg otserver brasiliyera
editor: markdown
dateCreated: 2023-10-19T02:47:25.774Z
---

## Informações Gerais
- **Protocolo**: 13.21
- **Tipo de Servidor**: Retro-PVP
- **Localização**: Brasil (São Paulo)
- **Taxa de Loot**: 2✕
- **Autoloot & Autobank**: Manage containers no jogo para loot, coins vão diretamente para sua conta bancária.
- **Maior segurança**: `bcrypt` salted e encrypted password, autenticação de dois fatores opcional
- **Vouchers Semanais**:
  - 4 horas de experiência em dobro
  - 12 horas de habilidade em dobro
- **Missões Grátis**: Acesse missões desbloqueadas para que você possa caçar spawns e os bosses que desejar

## Rates

**Experiência:** 10✕ para 2✕
![exp-rate.png](/exp-rate.png)

**Loot**: 1.5✕

**Skills/Magic Level:** 3✕

## Treinamento

- **Training weapons gratuitas e infinitas**: Tem 20% ou 1/5 da eficácia das exercise weapons (armas de exercício), mas duram para sempre!

- **Basic exercise weapons**: Armas de base (5x mais eficazes do que as infinitas). Você as obtém no jogo na loja, por gold, tokens ou [Brasiliyera Coins](https://Brasiliyera.com/shop).

- **Enhanced exercise weapons**: 20% mais eficazes do que as **Básicas**. Você as obtém no jogo por ouro, tokens ou [Brasiliyera Coins](https://Brasiliyera.com/shop).

- **Masterful exercise weapons**: 30% mais eficazes do que as **Básicas**. Você as obtém no jogo por gold, tokens ou [Brasiliyera Coins](https://Brasiliyera.com/shop).

## Blessings

- Todas as 7 blessings regulares disponíveis (você começa com as 5 básicas de graça)
- Use `!bless` no jogo para comprar bless
- Grátis até o nível 100
- Do nível 101 -> 399: `(nível - 100) * 60 + 1000` _(por bless)_
- Níveis 400+: 20.000 _(por bless)_

## Recompensas por nível

Você recebe algumas recompensas básicas de gold em alguns níveis:
- Nível 50: 20.000 gold
- Nível 100: 50.000 gold
- Nível 150: 100.000 gold
- Nível 200: 200.000 gold

## Comandos do Servidor
#### **Comandos Gerais:**
-   **!commands**
Veja uma lista de comandos disponíveis
-   **!aol**
Gera um Amuleto da Perda na sua mochila (Custa 50.000 ouro)
- **!autoloot on | !autoloot off**
Ativa ou desativa o autoloot
-   **!bless**
Adiciona todas as bênçãos disponíveis.
-   **!vip**
Verifique seu status VIP
-   **!flask on | !flask off**
Ativa ou desativa o recebimento de frascos vazios ao beber poções
-   **!emote on | !emote off**
Ativado fará com que feitiços sejam exibidos no chat.
Desativado removerá feitiços do chat e os exibirá como um emote (Texto laranja)
-   **!online**
Lista todos os jogadores online e seu status atual
-   **!serverinfo**
Lista o status do servidor
-   **!time**
Exibe a hora atual do mundo do jogo

#### **Comandos do banco**
*Não inclua os (colchetes) ao digitar esses comandos*
-   **!withdraw (quantidade)**
Retire dinheiro do seu banco
- **!transfer (nome do jogador), (quantia)**
Envie dinheiro para outro jogador
-   **!balance**
Verifique seu saldo bancário
- **!depot (valor) *ou* !depot all**
Deposite uma quantia específica de dinheiro em sua mochila no banco.
Ou deposite todo o dinheiro da sua mochila no banco.

#### **Comandos de houses (casas):**
-   **!buyhouse**
Fique na frente da porta para comprar a casa.
-   **!leavehous**
Fique dentro de casa para abandoná-la.
- **!sellhouse**
Fique na frente da porta, tenha outro jogador por perto, clique nele e ele iniciará uma negociação para vender a casa.

## Sistemas Personalizados
- As diamond arrows têm 1sqm a mais de tamanho e causam mais dano.
- O dano de wands e rods aumenta com o nível mágico (magic level) e o nível do jogador, e pode atingir até 4 criaturas.
- Todas as habilidades de combate melee foram fundidas em **melee fighting (combate corpo a corpo)**.
  - Swords (espadas) são armas poderosas de alvo único que causam mais dano rapidamente
    (+20% de velocidade de ataque, fórmula de dano regular).
  - Axes (machados) podem atingir até 5 criaturas que estão uma ao lado da outra
    (-20% de dano).
  - Clubs (clavas) causam dano em área do mesmo tamanho que as _diamond arrows_
    (-50% de dano).
  - Todas as training weapons (armas de treino) e imbuements que anteriormente afetavam sword, axe ou club agora afetarão o combate melee. First fighting (luta de punho) é considerado melee e foi ligeiramente aprimorado.
- **Nova habilidade**  **Runic fighting (combate rúnico)**: Você aumenta o nível de _runic fighting_ toda vez que causa dano a um inimigo com uma rune (runa). As runes recebem um boost (impulso) de dano com base na runic fighting do jogador.
- **Nova habilidade**  **Luck (sorte)**: Você aumenta o nível de _Luck_ looteando itens raros. Luck lhe proporciona mais loot e também lhe dá _critical hit chance_!
- Todo personagem começa com um acréscimo de 50% de critical hit damage (dano crítico). Isso se acumula com imbuements. Por exemplo, um jogador com o imbuement Powerful Strike causará 100% de critical damage.
- **Nova habilidade**  **Tonicity (Tonicidade)**: Você aumenta o nível de _tonicity_ simplesmente bebendo poções. Maior tonicidade torna as poções ligeiramente mais eficazes. O maior impacto é na média de cura de uma poção, não na quantidade máxima.
- **Nova habilidade**  **Dexterity (Destreza)**: Você aumenta o nível de _dexterity_ simplesmente recebendo dano. Quanto mais dano você recebe, mais essa habilidade aumenta. Atualmente, a dexterity fornece apenas uma pequena chance passiva de ativar "dodge".
- A **resistência máxima** que uma criatura pode ter a qualquer elemento é de 30%. Isso significa que todo elemento é de alguma forma viável em todas as situações.