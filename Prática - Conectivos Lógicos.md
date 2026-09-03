# Prática - Conectivos Lógicos

1. Eu estudei para a prova E fiz todos os exercícios.

Considere:

- **P** = “Eu estudei para a prova”
- **Q** = “Eu fiz todos os exercícios”
- Proposição: **P ∧ Q** (“P E Q”)

| P | Q | P ∧ Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

Na **conjunção (E)**, o resultado só é **Verdadeiro** quando **as duas** partes (P e Q) são verdadeiras ao mesmo tempo.

1. Eu vou ao cinema OU fico em casa assistindo séries.

Considere:

- **P** = “Eu vou ao cinema”
- **Q** = “Eu fico em casa assistindo séries”
- Proposição: **P ∨ Q** (“P OU Q”)

Na **disjunção (OU)**, o resultado só é **Falso** quando **as duas** partes são falsas ao mesmo tempo.

| P | Q | P ∨ Q |
| --- | --- | --- |
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |
1. SE eu acordar cedo, ENTÃO consiguirei pegar o ônibus.

Considere:

- **P** = “Eu acordar cedo”
- **Q** = “Eu conseguirei pegar o ônibus”
- Proposição: **P → Q** (“SE P, ENTÃO Q”)

Na **condicional (SE... ENTÃO...)**, a proposição só é **Falsa** quando **P é Verdadeiro** e **Q é Falso** (ou seja, acordei cedo, mas *não* consegui pegar o ônibus).

| P | Q | P → Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |
1. SE eu estudar muito, ENTÃO passarei na prova E ganharei um presente.

Defina as proposições simples:

- **P** = “Eu estudar muito”
- **Q** = “Eu passarei na prova”
- **R** = “Eu ganharei um presente”

A proposição é:

- **P → (Q ∧ R)** (“Se P, então Q e R”)

Agora a **tabela verdade**:

| P | Q | R | Q ∧ R | P → (Q ∧ R) |
| --- | --- | --- | --- | --- |
| V | V | V | V | V |
| V | V | F | F | F |
| V | F | V | F | F |
| V | F | F | F | F |
| F | V | V | V | V |
| F | V | F | F | V |
| F | F | V | F | V |
| F | F | F | F | V |

Observação: **uma condicional (P → S) só é falsa quando P é V e S é F**. Aqui, o “S” é **(Q ∧ R)**.

1. Eu vou jogar videogame OU ou estudar lógica de programação.

Definindo as proposições simples:

- **P** = “Eu vou jogar videogame”
- **Q** = “Eu vou estudar lógica de programação”

A proposição é uma **disjunção (OU)**:

- **P ∨ Q** (“P OU Q”)

A **tabela verdade** fica:

| P | Q | P ∨ Q |
| --- | --- | --- |
| V | V | V |
| V | F | V |
| F | V | V |
| F | F | F |

Na **disjunção (OU)**, o resultado só é **Falso** quando **as duas** proposições (P e Q) são falsas ao mesmo tempo.

1. Eu comi pizza E tomei refrigerante.

Definindo as proposições simples:

- **P** = “Eu comi pizza”
- **Q** = “Eu tomei refrigerante”

A proposição composta é uma **conjunção (E)**:

- **P ∧ Q** = “Eu comi pizza **E** tomei refrigerante”

### Tabela verdade (P ∧ Q)

| P | Q | P ∧ Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | F |

Na **conjunção (E)**, o resultado só é **Verdadeiro** quando **P e Q são verdadeiros ao mesmo tempo**.

1. SE eu tiver dinheiro ENTÃO viajarei nas férias.

Considere:

- **P** = “Eu tenho dinheiro”
- **Q** = “Eu viajarei nas férias”
- Proposição: **P → Q** (“SE P, ENTÃO Q”)

Na **condicional (→)**, a proposição só é **Falsa** quando **P é Verdadeiro** e **Q é Falso** (tenho dinheiro, mas não viajarei).

| P | Q | P → Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | V |
| F | F | V |
1. Eu lerei um livro SE E SOMENTE SE terminar meu trabalho.

Definindo as proposições simples:

- **P** = “Eu lerei um livro”
- **Q** = “Eu terminar meu trabalho”

A proposição composta é uma **bicondicional**:

- **P ↔ Q** (“P **se e somente se** Q”)

A bicondicional (**↔**) é **Verdadeira** quando **P e Q têm o mesmo valor** (ambas verdadeiras ou ambas falsas) e é **Falsa** quando **são diferentes**.

### Tabela verdade (P ↔ Q)

| P | Q | P ↔ Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | V |
1. SE estiver sol, ENTÃO irei à praia OU ao parque.

Considere as proposições simples:

- **P** = “Está sol”
- **Q** = “Eu irei à praia”
- **R** = “Eu irei ao parque”

A proposição composta é:

- **P → (Q ∨ R)** (“Se P, então Q ou R”)

Agora, a **tabela verdade**:

| P | Q | R | Q ∨ R | P → (Q ∨ R) |
| --- | --- | --- | --- | --- |
| V | V | V | V | V |
| V | V | F | V | V |
| V | F | V | V | V |
| V | F | F | F | F |
| F | V | V | V | V |
| F | V | F | V | V |
| F | F | V | V | V |
| F | F | F | F | V |

**Observação:** a condicional **P → S** só é **Falsa** quando **P = V** e **S = F**. Aqui, **S = (Q ∨ R)**, então só dá falso quando *está sol* (**V**) e *não vou nem à praia nem ao parque* (**Q = F** e **R = F**).

1. Eu farei um bolo SE E SOMENTE SE comprar os ingredientes.

Definindo as proposições simples:

- **P** = “Eu farei um bolo”
- **Q** = “Eu comprarei os ingredientes”

A proposição composta é uma **bicondicional**:

- **P ↔ Q** (“P *se e somente se* Q”)

A **tabela verdade** (P ↔ Q) fica:

| P | Q | P ↔ Q |
| --- | --- | --- |
| V | V | V |
| V | F | F |
| F | V | F |
| F | F | V |

**Regra:** na bicondicional (**↔**), o resultado é **Verdadeiro** quando **P e Q têm o mesmo valor** (ambos V ou ambos F) e é **Falso** quando **são diferentes**.