# Teste Técnico para Desenvolvedor PHP/Laravel

## Objetivo
Desenvolver uma aplicação básica usando Laravel que gerencie médicos, pacientes e atendimentos. A aplicação deve permitir o cadastro, a consulta, a atualização e a exclusão de cada uma dessas entidades.

## Requisitos Técnicos

### 1. Configuração Inicial
- Criar um projeto Laravel usando o Composer (versão 7 ou 11/diferencial).
- Configurar o ambiente de desenvolvimento utilizando Docker (diferencial).
- Aplicar o padrão de commits GitFlow no desenvolvimento.

### 2. Modelagem de Dados
- Criar as seguintes tabelas:
  - `pacientes`: deve conter informações como `id`, `nome`, `cpf`, `data_nascimento` e `email`.
  - `medicos`: deve conter `id`, `nome`, `crm` e `especialidade`.
  - `atendimentos`: deve registrar os atendimentos realizados, com `id`, `data_atendimento`, `medico_id` e `paciente_id`.

- Estabelecer os seguintes relacionamentos:
  - Um médico pode atender vários pacientes.
  - Um paciente pode ser atendido por vários médicos através dos atendimentos.

### 3. Desenvolvimento dos Models
- Criar Models para `Paciente`, `Medico` e `Atendimento` com seus respectivos relacionamentos.

### 4. CRUDs
- Desenvolver interfaces para o CRUD de cada entidade: pacientes, médicos e atendimentos.
- Utilizar Bootstrap para estilizar as páginas (diferencial).
- Implementação do padrão "Conventional Commits" para mensagens de commits.

### 5. Funcionalidades Adicionais
- Criar uma funcionalidade de relatórios que liste atendimentos por médico.

## Validações
- Será avaliado como foram realizadas as validações dos campos nos formulários, garantindo a integridade e correção dos dados.

## Entrega
- O código deve ser enviado para um repositório GitHub com o uso adequado do GitFlow.
- Documentar brevemente como configurar e rodar o projeto no `README.md`.
- Encaminhar o link do repositório junto com o currículo para o e-mail `jobs@beecoffee.com.br`.

## Avaliação
- Clareza e qualidade do código.
- Adesão aos requisitos e funcionamento das funcionalidades.
- Uso correto das ferramentas Laravel, padrões de design e melhores práticas.
- Implementação e robustez das validações de campos nos formulários.
