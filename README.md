- 👋 Hi, I’m @alksjfdoawkef
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...

<!---
alksjfdoawkef/alksjfdoawkef is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
import random

a=input("찍기 머신!!!\n-미룰래 말래에 대한 답을 원하면 1 \n-잘래 말래에 대한 답을 원하면 2 \n-나갈래 말래에 대한 답을 원하면 3\n-기타를 원하면 4\n를 입력하세요\n무엇을 선택하시겠어요?:")

if a == "1":
    b=["미룬다", "한다", "내일 나는 할 수 있을 것이다", "못할지도 모르지만 피곤하니 잔다","결과적으론 망치진 않을것이다","시험날 후회한다", "후회한다. 그냥 해라","너 이것도 못하니?", "주말에 후회하지만 결국 하긴 한다"]
    choicelist = random.choice(b)
    print("미루자 말자에 대한 컴퓨터의 생각: "+ choicelist)
elif a == "2":
    b = ["어짜피 잘 건데 좀 일찍 자도 문제될 건 없다", "그냥 해라 좀."]
    choicelist = random.choice(b)
    print("결괏값은??:"+choicelist)
elif a == "3":
    b= ["귀찮다","그래도 나가야한다"]
    choicelist = random.choice(b)
    print(choicelist+"고 하네요")
elif a == "4":
    b = input("어떤 것을 물어보실 건가요?:")
    while True:
        print("그만두시려면 숫자 10을 입력하세요")
        c = input("질문을 입력하세요: ")
        if c == "10":
            break
    choicelist = random.choice(d)
    print(b+"에 대한 컴퓨터의 생각은?: "+choicelist)
else:
    print("다시해")
#처음 질문으로 돌아가는 
