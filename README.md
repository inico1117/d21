# d21

>> sum = 0;
>> n = 1;
>> while n<1000
sum = sum+n;
n = n+1;
end
>> sum

sum =

      499500

A = [0,-1,4;9,-14,25;-34,49,64]
B = A;
for i = 1:3
    for j = 1:3
        if (B(i,j) < 0)
            B(i,j) = 0;
        end
    end
end
disp(B)
