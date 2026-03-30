🔄 Projeto Inverter Nome (C#)

Aplicação simples em C# (Console App) que recebe quatro nomes digitados pelo usuário e exibe esses nomes na ordem inversa.

📖 Sobre o Projeto

Este projeto foi desenvolvido com o objetivo de praticar:

Entrada e saída de dados no console
Manipulação de variáveis
Lógica de troca de valores (uso de variável auxiliar)
Estruturas básicas da linguagem C#
⚙️ Como Funciona

O programa solicita ao usuário que digite 4 nomes:

Nome #1
Nome #2
Nome #3
Nome #4

Depois disso, ele utiliza uma variável auxiliar para inverter a ordem dos nomes.

🔁 Lógica de Inversão

A inversão acontece da seguinte forma:

auxiliar = nome1;
nome1 = nome4;
nome4 = auxiliar;

auxiliar = nome2;
nome2 = nome3;
nome3 = auxiliar;

Isso faz com que:

O primeiro nome troque com o último
O segundo nome troque com o terceiro
🚀 Tecnologias Utilizadas
C#
.NET (Console Application)
▶️ Como Executar
Pré-requisitos
Ter o .NET SDK instalado
Passos
dotnet new console
dotnet run
💻 Exemplo de Execução
Digite o nome#1: Ana
Digite o nome#2: Bruno
Digite o nome#3: Carlos
Digite o nome#4: Daniela

Nomes inseridos na sequência Invertida:
Daniela
Carlos
Bruno
Ana
📌 Observações
O programa não limita ou valida os nomes digitados.
Funciona apenas com exatamente 4 entradas.
🔧 Melhorias Futuras
 Permitir quantidade variável de nomes
 Utilizar listas (List<string>)
 Implementar inversão automática com Reverse()
 Melhorar a interface do usuário
👩‍💻 Autora

Desenvolvido por Marielly Monteiro 💙
