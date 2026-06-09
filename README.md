# Sistema de Alerta Digital

Projeto acadêmico em HTML sobre lógica digital aplicada a um sistema de alerta para missão espacial.

## Integrantes

- Jhon Cutile Titirico - RM 571976
- Nickolas Emanuel - RM 573483

Turma: 1CCPF

## Como abrir o projeto

### Opção 1: Abrir direto no navegador

1. Abra a pasta do projeto.
2. Entre na pasta `outputs`.
3. Dê dois cliques no arquivo:

```text
projeto_mission_control_ai.html
```

O projeto será aberto no navegador.

### Opção 2: Abrir pelo VS Code

1. Abra a pasta do projeto no VS Code.
2. Entre na pasta `outputs`.
3. Abra o arquivo:

```text
projeto_mission_control_ai.html
```

4. Clique com o botão direito no arquivo e escolha abrir no navegador, ou use uma extensão como Live Server.

## Expressão lógica simplificada

A saída principal do sistema é `X`.

Expressão simplificada:

```text
X = AC + EF + D(B + NOT(A))
```

Em portas lógicas:

```text
X = (A AND C) OR (E AND F) OR (D AND (B OR NOT A))
```

Onde:

- `AND` representa multiplicação lógica.
- `OR` representa soma lógica.
- `NOT(A)` representa a negação da entrada `A`.

Quando `X = 1`, o alerta principal é acionado.
