# Agricultural Management System

Este é um sistema de gestão agrícola que ajuda a gerenciar dados relacionados a diferentes culturas, calcular a área de plantio e estimar os insumos necessários (por exemplo, fertilizantes, pesticidas) com base no tipo de cultura e na área plantada. A aplicação usa Python e Tkinter para fornecer uma interface gráfica simples que permite aos usuários inserir, atualizar, deletar e visualizar os dados das culturas.

## Funcionalidades

- Adicionar novos dados de cultura selecionando o tipo de cultura, inserindo as dimensões (comprimento e largura) e calculando automaticamente a área de plantio e os insumos necessários.
- Atualizar dados de cultura existentes selecionando uma linha na tabela e modificando os valores.
- Deletar culturas selecionadas da tabela.
- Carregar e salvar dados de culturas de/para um arquivo CSV (`data.csv`).
- A interface é construída usando Tkinter e permite o gerenciamento de dados em tempo real.

## Tecnologias

- **Python 3.x**
- **Tkinter** para a GUI
- **CSV** para armazenamento de dados

## Instalação

1. Clone o repositório ou baixe o código-fonte.

   ```bash
   git clone https://github.com/seu-usuario/sistema-gestao-agricola.git
   cd sistema-gestao-agricola
   ```

2. Verifique se o Python está instalado. Você pode verificar com o comando:

   ```bash
   python --version
   ```

3. Se o Python estiver instalado, você pode executar o programa diretamente.

## Como Executar

1. Abra o terminal ou prompt de comando na pasta do projeto.
2. Execute o script:

   ```bash
   python main2.py
   ```

3. A janela da aplicação será aberta, permitindo que você interaja com o sistema.

## Como Usar

1. **Adicionar Dados**:
   - Selecione uma cultura no menu suspenso.
   - Insira os valores de `Comprimento` e `Largura` (ambos devem ser numéricos).
   - Clique em **Adicionar Dados** para calcular a área e os insumos necessários para aquela cultura.
   - Os dados serão exibidos na tabela e salvos no arquivo `data.csv`.

2. **Atualizar Dados**:
   - Selecione uma linha na tabela.
   - Clique em **Atualizar** para modificar a cultura, o comprimento e a largura.
   - Os dados atualizados serão refletidos na tabela e salvos no arquivo `data.csv`.

3. **Deletar Dados**:
   - Selecione uma ou mais linhas na tabela.
   - Clique em **Deletar Selecionados** para remover as entradas.
   - Os dados serão atualizados na tabela e salvos no arquivo `data.csv`.

4. **Selecionar Tudo**:
   - Clique em **Selecionar Tudo** para selecionar todas as linhas da tabela.