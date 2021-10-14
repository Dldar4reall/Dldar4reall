- 👋 Hi, I’m @Dldar4reall
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
Dldar4reall/Dldar4reall is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
firstQ = "2 Rad To Deg"
Answer1 = float("114.6")
secondQ = "180 Deg To Rad"
Answer2 = float("3.14")
thirdQ = "1 Rev To Deg"
Answer3 = int("360")
fourthQ = "4 Rev To Rad"
Answer4 = float("25.12")
Results = int("0")

print (f"{firstQ}")
YourAnswer1 = float(input("? : ").strip())
if YourAnswer1 == Answer1 :
    print ("Good Job")
    Results += 1
else:
    print ("Wrong Answer")

print(f"{secondQ}")
YourAnswer2 = float(input("? : ").strip())
if Answer2 == YourAnswer2 :
    print("Good Job")
    Results += 1
else:
    print("Wrong Answer")

print(f"{thirdQ}")
YourAnswer3 = int(input("? : ").strip())
if Answer3 == YourAnswer3 :
    print("Good Job")
    Results += 1
else:
    print("Wrong Answer")

print(f"{fourthQ}")
YourAnswer4 = float(input("? : ").strip())
if Answer4 == YourAnswer4 :
    print("Good Job")
    Results += 1
else:
    print("Wrong Answer")

print(f"Your Points / {Results} Of 4")
