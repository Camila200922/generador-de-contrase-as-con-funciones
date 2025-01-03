import random
def gen_pass(pass_length, elements):
    password = ""
    for _ in range(pass_length):
        password += random.choice(elements)
    return password
def main():
    pass_length = int(input("Enter the length of the password: "))
    elements =  "+-*/#$Q=123445677890avsacaincaeina"
    password = gen_pass(pass_length, elements)
    print("genereador de contraseñas", password)
main()
