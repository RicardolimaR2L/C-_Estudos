# CSharp-Estudos

Repositório criado para guardar os códigos das aulas de C# (C-Sharp).

Utilizo o Visual Studio Code como IDE para desenvolver em C# com o framework .NET. Abaixo está um guia de como configurar e usar o Visual Studio Code para esse propósito.

## Como Usar o C# no Visual Studio Code

### Instalar o .NET SDK

1. **Download do .NET SDK**:
   - Acesse [dotnet.microsoft.com/download](https://dotnet.microsoft.com/download) e faça o download do .NET SDK.
   - Siga as instruções de instalação específicas para o seu sistema operacional.

2. **Verificar a Instalação**:
   - Abra o terminal ou prompt de comando e execute:
     ```bash
     dotnet --version
     ```
   - Isso deve retornar a versão do .NET instalada.

### Instalar Extensões no Visual Studio Code

1. **Abrir o Visual Studio Code**: Abra o Visual Studio Code no seu computador.

2. **Instalar a Extensão C#**:
   - Clique no ícone de Extensões no lado esquerdo da janela (ou pressione `Ctrl+Shift+X`).
   - Pesquise por "C#".
   - Clique em "Instalar" na extensão "C#" desenvolvida pela Microsoft.

### Criar e Executar um Projeto C#

1. **Criar um Novo Projeto**:
   - No terminal do Visual Studio Code, navegue até o diretório onde deseja criar o projeto.
   - Execute o comando para criar um novo console app:
     ```bash
     dotnet new console -n NomeDoProjeto
     cd NomeDoProjeto
     ```

2. **Abrir o Projeto no Visual Studio Code**:
   - Abra o diretório do projeto no Visual Studio Code:
     ```bash
     code .
     ```

3. **Executar o Projeto**:
   - No terminal do Visual Studio Code, execute o comando para rodar o projeto:
     ```bash
     dotnet run
     ```
Sinta-se à vontade para contribuir com melhorias e sugestões para este repositório.
