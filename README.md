# python-case1
#total price, product, product price
print('''PRODUCTS:
1.AATA      ($30)
2.GHEE      ($60)
3.DAL       ($20)
4.NOODLES   ($15)
5.CHOCOLATE ($25)''')
print()
print("Press their initial digits: ") #1 item
a=int(input())
print('Now enter the quantity: ')
b=int(input())
if a==1:c=a*30 
elif a==2:c=a*60
elif a==3:c=a*20
elif a==4:c=a*15
else: c=a*25
d=c*b
print()
print('TOTAL PRICE:')
print(d)
print()
print("Any other item you want to add? if no TYPE 0.") #2nd item
A=int(input())
print()
print("Enter the quantity: ")
B=int(input())
if A>0:
  if A==1:C=A*30
  elif A==2:C=A*60 
  elif A==3:C=A*20
  elif A==4:C=A*15 
  else: C=A*25
  D=C*B
  print('TOTAL PRICE:')
  print(D)
else:
  D=A*0
print()
print("Any other item you want to add? if no TYPE 0.") #3rd item
aa=int(input())
print("Enter the quantity: ")
bb=int(input())
if aa>0:
  if aa==1:cc=aa*30
  elif aa==2:cc=aa*60 
  elif aa==3:cc=aa*20
  elif aa==4:cc=aa*15 
  else: cc=aa*25
  dd=cc*bb
  print('TOTAL PRICE:')
  print(dd)
else:
  dd=aa*0
print()
print("Any other item you want to add? if no TYPE 0.") #4th item
aaa=int(input())
print("Enter the quantity: ")
bbb=int(input())
if aaa>0:
  if aaa==1:ccc=aa*30
  elif aaa==2:ccc=aa*60 
  elif aaa==3:ccc=aa*20
  elif aaa==4:ccc=aa*15 
  else: ccc=aaa*25
  ddd=ccc*bbb
  print('TOTAL PRICE:')
  print(ddd)
else:
  ddd=aaa*0
print()
print("Any other item you want to add? if no TYPE 0.") #5th
aaaa=int(input())
print("Enter the quantity: ")
bbbb=int(input())
if aaaa>0:
  if aaaa==1:cccc=aa*30
  elif aaaa==2:cccc=aa*60 
  elif aaaa==3:cccc=aa*20
  elif aaaa==4:cccc=aa*15 
  else: cccc=aaaa*25
  dddd=cccc*bbbb
  print('TOTAL PRICE:')
  print(dddd)
else:
  dddd=aaaa*0
print()
print('TOTAL PRICE:')
E=D+d+dd+ddd+dddd
print(E)
