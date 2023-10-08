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


