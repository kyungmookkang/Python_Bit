# Let's learn Python
-    1. git add
-    2. git commit
-    3. git checkout
-    4. git merge
 
 ##git +remote
-    1. git hub 저장소 만들기
-    2. git clone으로 pull하기
-    3. git push로 upload


# 파이썬 프로그래밍


1+1

kor = 90
eng = 100

test = 90 + 100
sum = kor + eng
avg = sum / 2

print('합계:', sum)
print('평균:', avg)

print("HEY HEY HEY")


num = 15
x = apple
y = orange

변수는 'Object' 객체 라고 불리운다.

variable = 123456            # 숫자
variable2 = "onetwothree"     # 문자

variable

variable2

variable2 + variable

!abc = 100

123

age = 100
Age = 1000

age, Age

vlookup(std!,$a:$b,2,false)

Computer = 'Mac'

x = 20

Computer = 1

x, Computer, age ,Age

### 숫자

i = 10
j = 100
k = -10000

i , j, k

f = 300.4

b = 3e3

print ("dude")

type(1)

type(1,0)

type(1e3)

1e3

1e3, 3.3333, 6/5

type(1+4J)

# 문자열

#문자열

a = '안녕'
b = 'halo'
a

type(str)

x = 'I am happy'

# 인덱스 범위
x[4:8]

x[4:]

x[-1]

x[-4:]

10 > 20

# Bool

True

False

10 > 20

10 > 20 ==True

type(True)

type(True), type(False)

# 연산자
산술 연산자: +,=,*,/,%,//,**

a = 10
b = 20

c = a + b * 10 - 5/5
c

7 ** 0

'=+, -+, *=, /='

x = 10
x += 10
x

x =+ 10
x

x /= 2
x

10 * 10

10 / 2

# 숫자 형식별 연산!

0 / 10

10.0 - 2

"호" * 100

ㅁ = "호"

ㅍ = "빵"

ㅁ + ㅍ 

    # 잘
    


ㅁ + 100

ㅁ * ㅍ

ㅁ + ㅍ * 100

ㅁ + str(1000)

del str

name = "홍길동"
print("내 이름은 " + name + " 입니다.")

del print

name1 = 'mook'
a = '나는 %s입니다.'% name1

print("내 이름은  + %s +  입니다." % name)

name = '홍길동'
addr = '서울'

print("내 이름은  + %s +  입니다." % (name, addr) )

age = 1000

print("내 이름은  + %s +  입니다." % (name, addr) )


#  .format()

"내 이름은 {} 이고, 주소는 {} 이고 나이는 {}".format(name, addr, age)

"내 이름은 {0} 이고, 주소는 {2} 이고 나이는 {1}".format(name, age, addr)

# practice format

 print('We are the {} who say "{}!"'.format('knights', 'Ni'))

'We are the {} who say "{}!"'.format('knights', 'Ni')

'{1} and {0}' .format('spam' , 'eggs')

'{0} and {1}' .format('spam' , 'eggs')

'This {} is {}' .format('ball', 'shit')

table = {'Tim': 123, 'Mook': 200, 'Joon': 121}
'Tim: {0[Tim]:d}; Mook: {0[Mook]:d};'Joon': {0[Joon]:d}'.format(table))

a = "옹"
type(a), type("홍")

"abc".upper()

"SDFsdfsdfsdfsdfSADFasfd".swapcase()

len("asdasd")

" asdasd ASD @!@#F" .strip()

msg = ['a', 'b', 'c'] #리스트
"#".join(msg)

"010-1234-123124".split("-")

# 프린트 

print("010", 1111, "9999", sep="-")

print("2021", "1", "1", sep="/")

print("안녕")
print("응...")
print("잘 지내니?", end="\n\n\n")

print("dd")

/n

\n

abc = None

name = input("이름을 입력하세요:")

a = int(input('첫 번째 숫자를 입력하세요:'))
b = int(input('두 번째 숫자를 입력하세요:'))
c = a + b

inch = float(input('인치(inch)를 입력하세요: '))

cm = inch * 2.54

print('센티미터 : .%.2f'%cm)

name = input('학생 이름을 입력하세요:')
kor = ()(input('국어 성적을 입력하세요:'))
eng = ()(input('영어 성적을 입력하세요:'))
math = ()(input('수학 성적을 입력하세요:'))

total = kor + eng + math
'avg' = total/3

print('name:황예린, 국어:%, 영어%d, 수학%d, 평균%.1점') %(name, kor, eng, math, avg)

# 주석 

# 한 줄 주석

"""
독 스트링은 문자열 이다.
""" 

help(print)

print.__doc__

조건:

 - True, Flase 판단 !
 - 크냐, 작냐, 같으냐, ....
    - 조건/비교/관계 연산자:
        - '<, >, =>, <=, ==, '

a = 100
b = 10

if a > b : 
    # 
    #
    #
    print("A is big")
else :
    #
    #
    print("A is small")
    
    
    
    
    
    

not False

x = int(input('숫자를 입력하세요 :'))

if x > 0 : 
    print('양수!')
    
else :
    print('0 또는 음수!')

x = int(input('숫자를 입력하세요 :'))

if x >= 65 or x < 7 : 
    print('Free')
    
else :
    print('$20')

x = int(input('숫자를 입력하세요 :'))

if x >= 65 or x < 7 : 
    print('Free')
    
else :
    print('$20')

name = input('name:')
name

name = input('name:')

if not name:
    print("Please try again")

a = 10

print("True") if a == 10 else print("False")

score = int(input('점수를 입력하세요 :'))

if score >= 90 : 
    grade = "A"
elif score >= 80 :
    grade = "B"
elif score >= 70 :
    grade = "C"
elif score >= 60 :
    grade = "D"
else :
    grade = "F"
    
    
print('score : %d' % score)
print('grade : %s' % grade)


