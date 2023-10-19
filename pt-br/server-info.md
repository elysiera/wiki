---
title: Server Info
description: 
published: true
date: 2023-10-19T02:55:35.312Z
tags: tibia mmorpg otserver brasiliyera
editor: markdown
dateCreated: 2023-10-19T02:47:25.774Z
---

## Informações Gerais
- **Protocolo**: 13.21
- **Tipo de Servidor**: Retro-PVP
- **Localização**: Brasil
- **Taxa de Loot**: 2✕
- **Autoloot & Autobank**: Manage containers no jogo para loot, coins vão diretamente para sua conta bancária.
- **Maior segurança**: bcrypt` salted e encrypted password, autenticação de dois fatores opcional
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

- **Armas de treinamento gratuitas e infinitas**: São 20% menos eficazes do que as armas de exercício regulares, mas duram para sempre!

- **Armas de exercício básicas**: Armas de base (5x mais eficazes do que as infinitas). Você as obtém no jogo na [Online Points](https://Brasiliyera.com/pages/online-points) loja, por ouro, tokens ou [Brasiliyera Coins](https://Brasiliyera.com/shop).

- **Armas de exercício aprimoradas**: 20% mais eficazes do que as **Básicas**. Você as obtém no jogo por ouro, tokens ou [Brasiliyera Coins](https://Brasiliyera.com/shop).

- **Armas de exercício magistrais**: 30% mais eficazes do que as **Básicas**. Você as obtém no jogo por ouro, tokens ou [Brasiliyera Coins](https://Brasiliyera.com/shop).

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

## Server Commands
#### **General commands:**
-   **!commands**
See a list of commands available
-   **!aol**
Spawn an Amulet of Loss into your backpack (Costs 50,000 gold)
- **!autoloot on | !autoloot off**
Enable or disable autoloot
-   **!bless**
Add all available blessings.
-   **!vip**
Check your VIP status
-   **!flask on	 | !flask off**
Enables or disables receiving empty flasks when drinking potions
-   **!emote on	 | !emote off**
On will make spells display in chat.
Off will remove spells from chat and display as an emote (Orange text)
-   **!online**
Lists all players online and their current status
-   **!serverinfo**
Lists the server status
-   **!time**
Displays the current game world time

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