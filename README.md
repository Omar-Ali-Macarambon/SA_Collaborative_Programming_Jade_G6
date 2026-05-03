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

# Now we create the code for the Q2 Grade
# Copy paste the code for Q1 but change Q1 to Q2
SA1 = (float(input("Please input the percent of your Summative Assesment 1 without the % symbol: ")))
SA2 = (float(input("Please input the percent of your Summative Assesment 2 without the % symbol: ")))
SA_Final = (((SA1 + SA2)/2)*0.7)
print("SA Final Grade = ", SA_Final,"%")

FA1 = (float(input("Please input the percent of your Formative Assesment 1 without the % symbol: ")))
FA2 = (float(input("Please input the percent of your Formative Assesment 2 without the % symbol: ")))
FA_Final = (((FA1 + FA2)/2)*0.3)
print("FA Final Grade = ", FA_Final,"%")

Q2_Ten = (SA_Final + FA_Final)
# Make the formula for the cumulative Q2 Grade
Q2 = ((Q1_Ten + (Q2_Ten * 2))/3)
if Q2 >= 96:
    Q2 = "1.00"
elif Q2 >= 90:
    Q2 = "1.25" 
elif Q2 >= 84:
    Q2 = "1.50" 
elif Q2 >= 78:
    Q2 = "1.75" 
elif Q2 >= 72:
    Q2 = "2.00" 
elif Q2 >= 66:
    Q2 = "2.25" 
elif Q2 >= 60:
    Q2 = "2.50" 
elif Q2 >= 55:
    Q2 = "2.75" 
elif Q2 >= 50:
    Q2 = "3.00" 
elif Q2 >= 40:
    Q2 = "4.00" 
elif Q2 < 40:
    Q2 = "5.00" 
print("Q2 Grade = ", Q2)

# Q3 Cumulative Grade

SA1 = (float(input("Please input the percent of your Summative Assesment 1 without the % symbol: ")))
SA2 = (float(input("Please input the percent of your Summative Assesment 2 without the % symbol: ")))
SA_Final = (((SA1 + SA2)/2)*0.7)
print("SA Final Grade = ", SA_Final,"%")

FA1 = (float(input("Please input the percent of your Formative Assesment 1 without the % symbol: ")))
FA2 = (float(input("Please input the percent of your Formative Assesment 2 without the % symbol: ")))
FA_Final = (((FA1 + FA2)/2)*0.3)
print("FA Final Grade = ", FA_Final,"%")

Q3_Ten = (SA_Final + FA_Final)
# Make the formula for the cumulative Q3 Grade
Q3 = ((Q2_Ten + (Q3_Ten * 2))/3)
if Q3 >= 96:
    Q3 = "1.00"
elif Q3 >= 90:
    Q3 = "1.25" 
elif Q3 >= 84:
    Q3 = "1.50" 
elif Q3 >= 78:
    Q3 = "1.75" 
elif Q3 >= 72:
    Q3 = "2.00" 
elif Q3 >= 66:
    Q3 = "2.25" 
elif Q3 >= 60:
    Q3 = "2.50" 
elif Q3 >= 55:
    Q3 = "2.75" 
elif Q3 >= 50:
    Q3 = "3.00" 
elif Q3 >= 40:
    Q3 = "4.00" 
elif Q3 < 40:
    Q3 = "5.00" 
print("Q3 Grade = ", Q3)
