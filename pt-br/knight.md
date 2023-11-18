---
title: Knight
description: 
published: true
date: 2023-11-18T05:15:26.254Z
tags: 
editor: markdown
dateCreated: 2023-11-18T05:15:26.254Z
---

# Knight

Knights são a única vocação que gerencia ativamente tanto poções de saúde quanto de mana. Devido ao seu tempo de recarga compartilhado, isso frequentemente leva a situações onde a escolha é apenas beber poções de saúde para sobreviver, enquanto não é possível recuperar mana para se libertar de um cerco. Além disso, cavaleiros têm sofrido um impacto desproporcional de mecânicas de dreno de mana. Esta reformulação remove completamente os efeitos do dreno de mana nos recursos de um knight. Por fim, as opções de feitiços de alvo único dos knights têm se mostrado insatisfatórias.

Estamos reformulando o sistema de recursos do knight e redesenhando todas as habilidades dos knights para funcionarem dentro dele. Ao refinar o sistema de recursos, os knights agora podem gerenciar simultaneamente a saúde e o recurso de combate de forma independente, oferecendo um ritmo de batalha mais suave e controlado. Esta mudança também é impactante no início do jogo, permitindo um sistema de progressão que se mostra tão viável quanto as outras vocações. Para abordar as rotações de alvo único dos knights, certos feitiços foram redefinidos com um propósito estratégico claro, proporcionando um nicho para muitas habilidades subutilizadas. Esses ajustes são projetados para elevar o estilo de jogo dos knights, proporcionando uma experiência de combate mais rica e robusta.

# :new: Novo Recurso: Rage (fúria)
- **Fúria Máxima**: 1000 pontos
- **Mecânicas de Fúria**: Substitui a mana. Aumenta com ações de combate designadas; decai passivamente ou regenera em direção a uma linha de base de 200.
- **Notas dos Desenvolvedores**: Nosso objetivo é criar um sistema de combate mais dinâmico, onde o gerenciamento de recursos se torna crucial para o seu sucesso no campo de batalha.

**Chave**
🟢  Representa geradores de fúria
🟥  Representa consumidores de fúria

# :crossed_swords: Reformulação de Habilidades & Feitiços
## Novos e Modificados Feitiços
:star:**Charge (`utani tempo hur`)**:star: 🟢 100 Fúria | :clock2: 12s de Recarga | Nível 25 | *Corre rapidamente até seu alvo.*
:star:**Phalanx (`utamo scuta`)**:star: 🟥 300 Fúria | :clock2: 8s de Recarga | Nível 14 | *Feitiço de Suporte: Gera um escudo baseado no nível e defesa que transfere 10% do dano recebido para ele, durando até 30s.*
**Mana Leech** irá "curar" seu escudo **Phalanx** enquanto estiver ativo

## Feitiços de Cura
**Bruise Bane (`exura infir ico`)** 🟥 100 Fúria | :clock2: 2s de Recarga | Nível 1
**Wound Cleansing (`exura ico`)** 🟥 100 Fúria | :clock2: 2s de Recarga | Nível 8
**Fair Wound Cleansing (`exura med ico`)** 🟥 100 Fúria | :clock2: 2s de Recarga | Nível 300
**Intense Wound Cleansing (``)** Sem custo de Fúria | :clock2: 3m (90s com upgrade WoD) de Recarga | Nível 80
**Recovery (`exura gran ico`)** Sem custo de Fúria | :clock2: 60s de Recarga/Duração | Nível 50
**Intense Recovery (`utura gran`)** Sem custo de Fúria | :clock2: 60s de Recarga/Duração | 100

## Feitiços de Ataque
**Brutal Strike (`exori ico`)** 🟢 350 Fúria | :clock2: 2s de Recarga | Nível 1
**Front Sweep (`exori min`)** 🟥 250 Fúria | 🧛‍♂️ 50% de Life Leech | :clock2: 2s de Recarga | Nível 20
**Whirlwind Throw (`exori hur`)** 🟥 100 Fúria | :clock2: 2s de Recarga | Nível 28
**Groundshaker (`exori mas`)** Sem custo de Fúria | :clock2: 16s de Recarga | Nível 33
**Berserk (`exori`)** 🟢 400 Fúria | :clock2: 2s de Recarga | Nível 35
**Inflict Wound (`utori kor`)** Sem custo de Fúria | :clock2: 30s de Recarga | Nível 40
**Fierce Berserk (`exori gran`)** 🟥 350 Fúria (300 com upgrade WoD) | :clock2: 2s de Recarga | Nível 50
**Annihilation (`exori gran ico`)** 🟥 600 Fúria | :clock2: 8s de Recarga | Nível 110
**Executioner's Throw (`exori amp kor`)** 🟥 1000 Fúria | :broken_heart: 30% da saúde máxima | :clock2: 8s de Recarga | Roda do Destino

## Feitiços de Suporte
**Challenge (`exeta res`)** 🟢 300 | :clock2: 4s de Recarga | Nível 20
**Train Party (`utito mas sio`)** Sem custo de Fúria | :clock2: 10s | Nível 32
**Protector (`utamo tempo`)** Sem custo de Fúria | :clock2: 6s de Recarga | Nível 55
**Blood Rage (`utito tempo`)** :broken_heart: 10% do HP atual | :clock2: 6s de Recarga | Nível 60
**Chivalrous Challenge (`exeta amp res`)** 🟥 150 Fúria (Sem custo de Fúria com upgrade WoD) | :clock2: 4s de Recarga | Nível 150
**Knight Familiar (`utevo gran res eq`)** :broken_heart: 30% do HP máximo | Nível 200

## Ajustes
**Poções de Mana** | **Fluidos de Mana** Usar qualquer poção de mana em um knight não adicionará recursos
**Itens de Jean Pierre** Comidas que restauram mana não restaurarão o recurso dos knights
**Comida e Item de Regeneração** A regeneração de comida e itens não afeta o recurso de fúria
**Mana Leech** Não faz nada a menos que **Phalanx** esteja ativo, caso em que se aplica ao escudo. Foi removido como opção de *armas* (mas mantido em *capacetes*).
