#!/usr/bin/python3
#num = [7,8,9,10];
#num = [3,3,7,13];
#num = [1,2,3,4];
num = [1,5,5,5];
sybol=['+','-','*','/'];

i1=0;
while i1<4:
    c1=0;
    while c1<4:
        i2 = 0;
        while i2<4:
            if i2!=i1:
                c2=0;
                while c2<4:
                    i3=0;
                    while i3<4:
                        if (i3!=i1 and i3!=i2):
                            c3=0;
                            while c3<4:
                                i4=0;
                                while i4<4:
                                    if(i4!=i1 and i4!=i2 and i4!=i3):
                                        calcStr1='(abs('+str(num[i1])+sybol[c1]+str(num[i2])+')'+sybol[c2]+str(num[i3])+')'+sybol[c3]+str(num[i4]);
                                        #print(calcStr,eval(calcStr1));
                                        if (eval(calcStr1)==24):
                                            print(calcStr1);
                                        elif not(sybol[c2]=='/' and eval(str(num[i1]) + sybol[c1] + str(num[i2]))==0):
                                            calcStr2 = '(' + str(num[i3]) + sybol[c2] + 'abs(' + str(num[i1]) + sybol[c1] + str(num[i2]) + ')' + ')' + sybol[c3] + str(num[i4]);
                                            # print(calcStr,eval(calcStr2));
                                            if (eval(calcStr2) == 24):
                                                print(calcStr2);
                                    i4=i4+1;
                                c3=c3+1;
                        i3=i3+1;
                    c2=c2+1;
            i2=i2+1;
        c1=c1+1;
    i1=i1+1;
