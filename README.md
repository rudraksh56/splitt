# splitt1
a='acddaccadd'
b={}
for i in a:
    if(i in b):
        b[i]+=1
    else:
        b[i]=1
print(b)

#splitt2

a='he is a good boy and he is a bad boy and he is'.split( )
b={}
for i in a:
    if(i in b):
        b[i]+=1
    else:
        b[i]=1
print(b)            
