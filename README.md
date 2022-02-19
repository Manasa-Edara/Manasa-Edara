- 👋 Hi, I’m @Manasa-Edara
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach mehttps://github.com/Manasa-Edara/Manasa-Edara/blob/f7750637c3e6a00b1a6ef46470f46885fc9485e0/Aa
https://www.onlinegdb.com/online_python_compiler
#PROGRAM TO PRINT COUNT OF N PRIME NUMBERS
def isprime(n):
    for i in range (2,n):
        if n%i==0:
            return False
        return True 
n=int(input('enter n:'))
count=0
for i in range(2,n+1):
    if isprime(i):
        count=count+1
        print(i,end=' ')
        print(count)

OUTPUT:
enter n:10
3    1
5    2
7    3
9    4
