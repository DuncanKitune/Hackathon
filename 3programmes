void main() {
  displayPersonalInformation();
  performMathematicalOperations();

  int marks = 85;
  determineGradeBasedOnMarks(marks); //pass marks as an arguement
}

displayPersonalInformation() {
  String name = "Jacob Abraham";
  int age = 30;
  String school = "PLP Academy";
  String hobby = "Travelling";

  print(
      "My name is $name. I am $age years old. I attend $school school. I like $hobby during my free time.");
}

performMathematicalOperations() {
  int a = 11;
  int b = 20;
  double c = 9 / 13;

  int add({required int a, required int b}) => a + b;
  int subtract({required int a, required int b}) => a - b;
  double multiply({required int a, required double c}) => a * c;

//Calling the function with named arguements
  print(
      "So far I can design a code to perform Addition eg a:11+b:20: = ${add(a: a, b: b)}");
  print(
      "and also perform Subtraction eg a:11-b:20: =  ${subtract(a: a, b: b)}");
  print("and Multiplication eg a:11*(c:9/13): = ${multiply(a: a, c: c)}");
}

String determineGradeBasedOnMarks(int marks) {
  if (marks > 85) {
    return "Excellent";
  } else if (marks >= 75 && marks <= 85) {
    return "Very Good";
  } else if (marks >= 65 && marks < 75) {
    return "Good";
  } else {
    return "Average";
  }
}

