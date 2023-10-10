a = 142342.4341
b = 1534534.453451
c = 153453.23261
abc = [int(a/b), int(b-c), int(c+a)]
print(abc[1])

d = 1
f = 3
df = ['d', 'f']
print(df[0])
aa = ['дориас']
bb = ['кинг']
ab = 2*2
bc = 2/2
cb = 2-2
cd = 2+2
abcd = ['ab', int(bc), 'cb', 'cd']
print(abcd[1])

dd = ['дориас', 'кинг']
text = len(dd)
print(str(text))

s = ['первое', 'второе', 'третье']
f = 1
print(s[f])
print(len(s))
r = ['Дориасу', 'Эриалу', 'Айлин']
q = ['первое', 'второе', 'третье']
for rr in r:
    for qq in q:
        print(rr)
        print(qq)

numbs = [1,2,3,4,5,6,7,8,9]
for numb_1 in numbs:
    for numb_2 in numbs:
        print(numb_1, '*', numb_2, '=', numb_1 * numb_2)
print()

tests = range(0,11)
for test_1 in tests:
    print(test_1)

for i in range(0,12):
    print('число от', str(i))

for i in range(0,10):
    print(i + (i-1))

print()

a = ''
for i in reversed(range(0, 11)):
    a = a + str(i) + ', '
a = a + 'поехали!'
print(a)
x = 6
a = (x > 5)
print(a)

sad = 1
if sad == 1:
    print('штиль')
else:
    print('ничего')


for god in range(101):
    if god >= 100:
        print(god, ' Yas')
    elif god <=50:
        print(god, 'ну не знаю')
    else:
        print(god, ' No')

for ros in range(10):
    if ros == 1:
        print('А нам всеровно', ros, 'раз бегать')
    elif god ==5:
        print('А нам всеровно', ros, 'раз бегать больше')
    else:
        print('А мне все ровно')

for gos in range(1,6):
    if gos > 1:
        print('А нам всеровно', gos, 'раз бегать')
    elif god > 4:
        print('А нам всеровно', gos, 'раз бегать больше')
    else:
        print('А мне все ровно')

for ii in range(10):
    if ii <=1:
        print('Если', ii, "хорошо")
    elif ii ==2 or ii == 3:
        print('Если', ii, "не плохо")
    elif ii >=4 and ii <= 5:
        print('Если', ii, "не No плохо")
    else:
        print('пофиг')

for a in range(5):
    if a <=1:
        print('yas')
    elif a >=2 and a <=3:
        print('or')
    else:
        print('No')

for current_hour in range(0, 24):
    print("На часах " + str(current_hour) + ":00.")

    if current_hour >= 6 and current_hour <= 11:
        print('Доброе утро!')
    elif current_hour >= 12 and current_hour <= 17:
        print('Добрый день!')
    elif current_hour >= 18 and current_hour <= 22:
        print('Добрый вечер!')
    elif current_hour <= 5 or current_hour >= 23:
        print('Доброй ночи!')

for i in range(0,10):
    if i == 0:
        print('iiii', i, 'aaaa')
    elif i >= 1 and i <= 1:
        print('sss', i,'sss')
    else:
        print('ddd')


wtf = False
if not wtf:
   print('Перевертыш')
elif wtf:
    print("не перевертышь")

a =6
b = False
c = 16
if not b or a <= 4 and c > 22:
    print('yes')
else:
    print('No')

a =6
b = False
c = 16
if (not b or a <= 4) and c > 22:
    print('yes')
else:
    print('No')

if not b or a <= 4 and c > 22:
    print('yes')
else:
    print('No')

a = not True
print(a)