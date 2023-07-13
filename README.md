# python_amalot5
pythonda if, elif va else lar bilan ishlash

kun=input("Bugun kun nima? ")
if kun.lower()=='shanba' or kun.lower()=='yakshanba':
    print("Bugun dam olish kuni")
else:
    print("Bugun dars kuni")

menu=["osh",'manti','tandir','somsa']
ovqat=input("nima ovqat buyurtma berasiz? ")
if ovqat.lower() in menu:
    print("Buyurtma berildi")
else:
    print('Uzr bizda bunday ovqat yo\'q')

cars=["malibu","lasette","kia","bmw","matiz"]
for car in cars:
    if car=="kia":
        print(car.upper())
    else:
        print(car.title())


ism=input("Ismingiz kim?\n>>> ")
if ism.lower()!="mavlon":
    print(f"Kechirasiz {ism.title()}  biz Mavlonni kutyapmiz")
else :
    print("Salom Mavlon xush kelibsiz")


son=float(input("\nSonni kiriting (-10<n<10) : n="))
if -10<son<10 :
    print(f"Siz kiritgan {son} soni shu oraliqqa tegishli")
else:
    print(f"Siz kiritgan {son} soni bu oraliqda mavjud emas") 


login=input("Loginingizni kiriting ")
if len(login)>=7:
    print("Xush kelibsiz")
else:
    print("Kechirasiz login parol kamida sakkizta bo'lishi kerak")

