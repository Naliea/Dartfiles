 void main() {
  // Integer data type (int)
  int age = 25;
  print('Age: $age');

  // Double data type
  double weight = 65.5;
  print('Weight: $weight');

  // String data type
  String name = 'John Doe';
  print('Name: $name');

  // List data type (Array)
  List<int> numbers = [1, 2, 3, 4, 5];
  print('Numbers: $numbers');

  // Accessing elements in a list
  print('First number: ${numbers[0]}');
  print('Last number: ${numbers[numbers.length - 1]}');

  // Modifying elements in a list
  numbers[0] = 10;
  print('Modified Numbers: $numbers');

  // Map data type (Dictionary)
  Map<String, dynamic> person = {
    'name': 'Alice',
    'age': 30,
    'isStudent': false,
  };
  print('Person: $person');

  // Accessing values in a map
  print('Name: ${person['name']}');
  print('Age: ${person['age']}');
  print('Is Student: ${person['isStudent']}');
}
