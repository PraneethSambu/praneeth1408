def l_s(l,n,key):  
    for i in range(0, n):  
        if (l[i] == key):  
            return i  
    return -1  
l = [10,35,42,51,62]  
key =  16 
n = len(l)  
res = l_s(l, n, key)  
if(res == -1):  
    print("Element not found")  
else:  
    print("Element found at index: ", res)
