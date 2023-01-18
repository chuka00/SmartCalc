# SmartCalc 😎
SmartCalc is a class library for simple mathematical operations.

## Installation
1. Install Visual Studio 2022 for Windows with a .NET Core-related workload.
2. You can install the 2022 Community edition for free from visualstudio.microsoft.com, or use the Professional or Enterprise edition.

### Prerequisites
1. An understanding of C# and NuGet Packages
2. Visual Studio

## Usage
You can install this NuGet package into any .NET project if that package supports the same target framework as the project. To use SmartCalc in your project, kindly follow these steps:

#### Installation using Visual Studio
1. In the Solutions Explorer of your project, Right-click on project dependencies 

2. Select manage Nuget packages

3. From the Browse tab, search for **SmartCalc**, select it in the list, and then select Install.

#### To install our package using the .NET CLI, run: *dotnet add package SmartCalc --version 1.0.1* 

4. In your project, simply instantiate the operations class before usage.  

## Sample
This is a sample of a mathematical operation in the package:
```
public int Addition(int a, int b)
        {
            return a + b;
        }      
```
Each method takes in two (2) parameters of type int and returns a value of type int too.

## Demonstration 
```
namespace CalcutexDemoLibraryClient
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
