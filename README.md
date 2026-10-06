void main() {

  //Section A: Beginner Questions
  
  // Q1 Addition of Numbers
  
  print("Addition");
  int a1 = 10;
  int b1 = 5;
  int result = a1 + b1;
  print('the sum of $a1 and $b1 is: $result');

  print("____________________________________________________");

  //   // Q2 Subtraction of Numbers
  
  print("Subtraction");
  
  int a2 = 20;
  int b2 = 8;
  int result2 = a2 - b2;
  print('the subtrction of $a2 and $b2 is: $result2');

  print("____________________________________________________");

  //   // Q3 Multiplication of Numbers
  
  print("Multiplication");
  
  int a3 = 6;
  int b3 = 7;
  int result3 = a3 * b3;
  print('the subtrction of $a3 and $b3 is: $result3');

  print("____________________________________________________");

  //   // Q4 Divion of Numbers
  
  print("Divison");
  
  int a4 = 30;
  int b4 = 5;
  double result4 = a4 / b4;
  print('the subtrction of $a4 and $b4 is: $result4');

  print("____________________________________________________");

  //   // Q5 All Operations
  
  print("All Operations");
  

  int num1 = 15;
  int num2 = 3;
  int sum = num1 + num2;
  int sub = num1 - num2;
  int multi = num1 * num2;
  double division = num1 / num2;

  print('the Addtition of $num1 and $num2 is: $sum');
  print('the Subtrction of $num1 and $num2 is: $sub');
  print('the Multiplication of $num1 and $num2 is: $multi');
  print('the Division of $num1 and $num2 is: $division');

  print("____________________________________________________");

  //   // Q6. Shopping Calculation

  int penCosts = 50;
  int noteBookCosts = 100;
  int totalPrice = penCosts + noteBookCosts;
  print("Shopping Calculation");
  print("The Total Cost of $penCosts and $noteBookCosts is: $totalPrice");

  print("____________________________________________________");

  // Q7. Age Calculation
  
  int currentAge = 20;
  int futureAge = 20 + 5;
  print('''
   The crrent Age is : $currentAge
   Age After 5 years will be : $futureAge
    ''');

  print("____________________________________________________");

  // Q8. Rectangle

  print("Rectangle : ");
  
  int length = 10;
  int width = 5;
  int area = length * width;
  print("the Area of Rectangle of length $length and width $width is: ${area}");

  print("____________________________________________________");

  //Q9. Average of Marks

  print("Average of Marks : ");
  
  int marks1 = 70;
  int marks2 = 80;
  int marks3 = 90;
  int obtainMarks = marks1 + marks2 + marks3;
  double avg = (obtainMarks / 300) * 100;
  print('''
   the Average Of $marks1,$marks2 and $marks3 is : $avg%
    ''');
  print("____________________________________________________");

  //   Q10 Simple Calculatore
  
  print("Simple Calculatore");

  int number1 = 100;
  int number2 = 19;
  int sum1 = number1 + number2;
  int sub1 = number1 - number2;
  int multi1 = number1 * number2;
  double division1 = number1 / number2;

  print('the Addtition of $number1 and $number2 is: $sum1');
  print('the Subtrction of $number1 and $number2 is: $sub1');
  print('the Multiplication of $number1 and $number2 is: $multi1');
  print('the Division of $number1 and $number2 is: $division1');

  print("____________________________________________________");

  //Section B: Slightly Challenging
  
  // Q11 Operator Precedence
  
  print("Operator Precedence");

  int a = 10;
  int b = 2;
  int produce = (a + b * 3);
  print("The Produce of $a and $b is: $produce");
  print("____________________________________________________");

  // Q12. Shopping Bill

  print("Shopping Bill");

  int price = 500;
  int quantity = 4;
  int finalPrice = price * quantity;
  print("The Total Amount is: $finalPrice");

  print("____________________________________________________");

  // Q13 Money Remaining
  
  print("Money Remainin");
  
  int moneyHave = 1000;
  int moneySpend = 350;
  int moenyLeft = moneyHave - moneySpend;
  print("the Total money left is : $moenyLeft");

  print("____________________________________________________");

  // Q14 Student Marks
  
  print("Student Marks : ");
  
  int stdMarks1 = 75;
  int stdMarks2 = 80;
  int stdMarks3 = 85;
  int stdMarks4 = 90;
  int obtainMarks4 = stdMarks1 + stdMarks2 + stdMarks3 + stdMarks4;
  double avgMarks = (obtainMarks4 / 400) * 100;
  print('''
   the Average Of $stdMarks1,$stdMarks2, $stdMarks3, and $stdMarks4 is : $avgMarks%
     ''');
  print("____________________________________________________");

  // Q15. Time Conversion

  print("Time Conversion");

  int hours = 5;
  int hrToMin = 60;
  int totalMins = hours * hrToMin;
  print("The Total Minutes of hours of $hours is: $totalMins");
}
