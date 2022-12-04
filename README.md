# C# 10 Pluralsight Path

## C# - The Big Picture

### Discovering C#

**Object Oriented with Functional Features**

`static void Main()
{
  var numbers = new int[] { 1, 2, 3, 4, 5 };
  var type = numbers.GetType(); 
  
  do
  {
    (Console.WriteLine(type.FullName);
    type = type.BaseClass;
  }
  while (type != null)
}`
