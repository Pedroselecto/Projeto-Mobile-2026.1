# Documentação Projeto de quadras

## Funcionalidades

### Agendamento de espaço

**Como** um condômino do Cidade Jardim

**Eu quero** realizar o agendamento de um espaço comum

**Para** utilizá-lo por um período específico

**Cenário 1: Agendar Espaço**

- **Dado** que estou autenticado no sistema e estou em dia com as taxas de condomínio
- **E** vou realizar o agendamento de uma quadra
- **Quando** seleciono uma data disponível
- **Então** preciso ser notificado caso a reserva seja realizada com sucesso

### Cancelamento de reserva

**Como** um condômino do Cidade Jardim que realizou um agendamento

**Eu quero** cancelar o agendamento do espaço comum

**Para** liberar o horário para outros moradores que possam querer agendá-lo

**Cenário 1:** Cancelamento de uma reserva

- **Dado** que estou autenticado no sistema e possuo agendamentos ativos
- **E** vou até a página de agendamentos ativos
- **Quando** seleciono a opção “desfazer agendamento” em uma das reservas ativas
- **Então** preciso ver uma mensagem de confirmação e, depois de confirmar, preciso ser notificado de que a reserva foi cancelada

### Cadastrar conta

**Como** um administrador 

**Eu quero** cadastrar uma nova conta para usuário

**Para** que um novo usuário possa acessar o sistema de agendamento de espaços comuns

**Cenário 1:** Cadastrar conta

- **Dado** que estou autenticado no sistema como um administrador
- **E** vou realizar o cadastro de um novo morador no sistema
- **Quando** preencho os dados do novo usuário e confirmo
- **Então** preciso ver uma confirmação de que o cadastro foi realizado com sucesso e receber o login que o novo usuário deve usar
