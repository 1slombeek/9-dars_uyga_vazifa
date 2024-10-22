class Odam:
    def __init__(self,ism):
        self.ism=ism
    def salomlashish(self):
        print(f"Salom {self.ism}")
x=input("Ism kiritong:")
odam=Odam(x)
odam.salomlashish()
