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

>> s1 = 'String'

s1 =

    'String'

>> s2 = 'Example'

s2 =

    'Example'

>> [s1 s2]

ans =

    'StringExample'

>> [s1;s1]

ans =

  2×6 char 数组

    'String'
    'String'
>> s = 'aardvark';
>> 'a' == s

ans =

  1×8 logical 数组

   1   1   0   0   0   1   0   0

>> s(s == 'a') = 'Z'

s =

    'ZZrdvZrk'
>> for j = 1:l
s1(j) = s2(l);
l = l-1;
end
>> s1

s1 =

    'gnirtS'
    
>> student.name = 'John Doe'
>> student.name = 'John Doe';
>> student.id = 'jd2@sfu.ca';
>> student.number = 301073268;
>> student.grade = [100,75,73;95,91,85.5;100,98,72];
>> student(2).name = 'Ann Lane';
>> student(2).id = 'aln4@sfu.ca';
>> student(2).num = 301078853;
>> student(2).grade = [95 100 90;...];
95 82 97;100 85 100];
>> student

student = 

  包含以下字段的 1×2 struct 数组:

    name
    id
    number
    grade
    num
