using System;
using System.Threading;

class Coletor
{
    static void Main()
    {

        Console.WriteLine("===================================");
        Console.WriteLine("==========SEJA-BEM-VINDO===========");
        Console.WriteLine("===================================");
        Console.WriteLine("....Coletor De Informações 1.0....");
        
        Thread.Sleep(3000);
        Console.Clear();

        Thread.Sleep(2000);
        Console.Write("Digite Suas Informações...");
        Console.Write("\n===========================");

        
        Thread.Sleep(2000);
        Console.Write("\n");
        Console.Write("\nDigite seu nome: ");
        Thread.Sleep(2000);


        string nome = Console.ReadLine();

        Thread.Sleep(2000);
        Console.Write("Digite sua Idade: ");
        

        int idade = int.Parse(Console.ReadLine());

        Thread.Sleep(2000);    
        Console.Write("Digite sua Cidade: ");
        string cidade = Console.ReadLine();

        Thread.Sleep(2000);
        Console.Write("Digite seu CPF: ");
        int cpf = int.Parse(Console.ReadLine());
        
        
        Console.Clear();

        
        Console.Write("Coletando Suas Informações....");

        Console.Write("\n========================");

        Thread.Sleep(3000);
        Console.Write("\nInformações Coletada: ");

        
        Thread.Sleep(2000);
        Console.Write("\n");
        Console.Write($"\nNome: {nome}");
        Console.Write($"\nIdade: {idade}");
        Console.Write($"\nCidade: {cidade}");
        Console.Write($"\nCPF: {cpf}");
        Console.Write("\n");
        
    }

}
