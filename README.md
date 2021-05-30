# factors-find
def factor(n,p):
    l=[]
    for i in range(1,n+1):
        if n%i==0:
            l.append(i);
    if len(l)<p:
        return 0;
    else:
        return l[p-1];
f=factor(2,3)
print(f)
