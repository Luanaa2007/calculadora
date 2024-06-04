# calculadora
class Calculadora:
    def somar(self, n1, n2):
        Result = n1+n2
        return(Result)
    def subtrair(self, n1, n2):
        Result = n1-n2
        return(Result)
    def multiplicar(self, n1, n2):
        Result = n1*n2
        return(Result)
    def dividir(self, n1, n2):
        Result = n1/n2
        return(Result)

        segunda parte

from calculadora import Calculadora
minha_calculadora = Calculadora()

result = minha_calculadora.somar(23, 78)
result2 = minha_calculadora.subtrair(89, 47)
result3 = minha_calculadora.dividir(34, 79)
result4 = minha_calculadora.multiplicar(34, 21)
print(result)
print(result2)
print(result3)
print(result4)
