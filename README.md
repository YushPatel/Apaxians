using System;



public class GroupAssignment3
{
public static void Main(string[] args)
{

string originalName = Console.ReadLine();
string modifiedName = " ";
char symbol = ' ';
foreach (char y in originalName)
{
if(y == symbol)
{
continue;
}
else
{
symbol = y;
modifiedName += y;
}
}
Console.WriteLine(modifiedName);
}
}
