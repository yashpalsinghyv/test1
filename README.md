# practical marks
practical_marks = float(input("Enter the practical marks: "))
# theory marks
theory_marks = float(input("Enter the theory marks: "))

# use AND and OR operator to Check if it passes the condition 
if (practical_marks >= 40 and theory_marks >= 30) or (practical_marks + theory_marks) >=70:
  print("\nYou are successful")
else:
  print("\nYou are not successful")
