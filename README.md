# Bacterias
using System;

class Program
{
    static void Main(string[] args)
    {
        Console.WriteLine("--- Colônia de Bactérias ---");
        Console.Write("Qual o número de indivíduos? ");
        double n = double.Parse(Console.ReadLine());

    double t = 2 * Math.Log(n / 2000, 2);

    Console.WriteLine($"A colônia atingirá {n} indivíduos em {t.ToString("F1")} horas.");
}
}