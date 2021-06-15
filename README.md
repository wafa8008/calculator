# BMI CALCULATOR 
weight=float(input())
height=float(input())

a=weight/(height**2)
if(a<18.5):
    print("Underweight")
elif(a>=18.5 and a<25):
    print("Normal")
elif(a>=25 and a<30):
    print("Overweight")
elif(a>30):
    print("Obesity")

