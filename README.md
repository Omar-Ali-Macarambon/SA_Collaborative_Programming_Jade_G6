# Create the foundation for the First Quarter tentative Grade
# Q1 = Tentative Grade of Q1
SA1 = (float(input("Please input the percent of your Summative Assesment 1 without the % symbol: ")))
SA2 = (float(input("Please input the percent of your Summative Assesment 2 without the % symbol: ")))
SA_Final = (((SA1 + SA2)/2)*0.7)
print("SA Final Grade = ", SA_Final,"%")

FA1 = (float(input("Please input the percent of your Formative Assesment 1 without the % symbol: ")))
FA2 = (float(input("Please input the percent of your Formative Assesment 2 without the % symbol: ")))
FA_Final = (((FA1 + FA2)/2)*0.3)
print("FA Final Grade = ", FA_Final,"%")

Q1_Ten = (SA_Final + FA_Final)
if Q1_Ten >= 96:
    Q1 = "1.00"
elif Q1_Ten >= 90:
    Q1 = "1.25" 
elif Q1_Ten >= 84:
    Q1 = "1.50" 
elif Q1_Ten >= 78:
    Q1 = "1.75" 
elif Q1_Ten >= 72:
    Q1 = "2.00" 
elif Q1_Ten >= 66:
    Q1 = "2.25" 
elif Q1_Ten >= 60:
    Q1 = "2.50" 
elif Q1_Ten >= 55:
    Q1 = "2.75" 
elif Q1_Ten >= 50:
    Q1 = "3.00" 
elif Q1_Ten >= 40:
    Q1 = "4.00" 
elif Q1_Ten < 40:
    Q1 = "5.00" 
print("Q1 Grade = ", Q1)
