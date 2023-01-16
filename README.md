# SmartCalc 😎

SmartCalc is a class library for simple mathematical operations. The mathematical operations includes:
1. Addition(int a, int b);

2. Subtraction(int a, int b);

3. Multiplication(int a, int b);

4. Division(int a, int b);

5. Modulus(int a, int b);

Each method takes in two (2) parameters of type int and returns a value of type int too.


`#` Installation

`###`Prerequisites

Install Visual Studio 2022 for Windows with a .NET Core-related workload.

You can install the 2022 Community edition for free from visualstudio.microsoft.com, or use the Professional or Enterprise edition.

You can install this NuGet package into any .NET project if that package supports the same target framework as the project. To use SmartCalc in your project, kindly follow these steps:

`##`Usage
1. In your Visual Studio, Select Project > Manage NuGet Packages.

2. In the NuGet Package Manager page, choose nuget.org as the Package source.

3. From the Browse tab, search for **SmartCalc**, select it in the list, and then select Install.

4. In your project, simply instantiate the operations class before usage.  

`###`Code Sample
```namespace CalcutexDemoLibraryClient
{
    internal class Program
    {
        static void Main(string[] args)
        {

            Operations operation = new Operations();
            var result =  operation.Subtraction(10, 5);
            Console.WriteLine(result);
            var result2 = operation.Addition(10, 5);
            Console.WriteLine(result2);
            var result3 = operation.Multiplication(10, 5);
            Console.WriteLine(result3);
            var result4 = operation.Division(10, 5);
            Console.WriteLine(result4);
            var result5 = operation.Modulus(10, 4);
            Console.WriteLine(result5);
        }
    }
}
```
