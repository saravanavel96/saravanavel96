- 👋 Hi, I’m @saravanavel96
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...

<!---
saravanavel96/saravanavel96 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->import csv
with open("text.csv",'r') as file:
    reader = csv.reader(file)
    for row in reader:
        print(row)
        
