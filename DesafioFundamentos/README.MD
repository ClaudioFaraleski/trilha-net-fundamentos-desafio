# Trilha .NET Fundamentos - Desafio
## WEX - End to End Engineering

### 💻 Sobre o Projeto
Sistema de gerenciamento de estacionamento desenvolvido em C# como parte do desafio de fundamentos .NET.

### 🚗 Funcionalidades

1. **Inicialização do Sistema**
   - Define preço inicial
   - Define preço por hora

2. **Menu Principal**
   - 1: Cadastrar veículo
   - 2: Remover veículo
   - 3: Listar veículos
   - 4: Encerrar programa

### 📋 Como Funciona

#### Cadastrar Veículo
- Digite a placa do veículo
- Sistema verifica se o veículo já está cadastrado
- Caso não esteja, adiciona o veículo à lista

#### Remover Veículo
- Digite a placa do veículo
- Sistema verifica se o veículo existe
- Informa quantidade de horas estacionado
- Calcula valor total (preço inicial + preço por hora * tempo)
- Remove o veículo da lista

#### Listar Veículos
- Exibe todos os veículos estacionados
- Caso não haja veículos, exibe mensagem informativa

### 💰 Cálculo do Valor
- Valor Total = Preço Inicial + (Preço por Hora × Tempo Estacionado)

### 🔧 Tecnologias Utilizadas
- C# (.NET)
- Programação Orientada a Objetos
- Listas e Coleções
- Estruturas de Controle

### 📌 Observações
- O sistema armazena as placas em memória
- Valores monetários são tratados como decimal
- Validações de entrada implementadas

### ✨ Melhorias Possíveis
- Persistência de dados
- Interface gráfica
- Relatórios detalhados
- Histórico de utilização
