                           Dictionary Problems with Answers       Priyanka M
   			  ----------------------------------      Mail:priyankakumbra@gmail.com

1)Write a program in the following steps
a. Roll a die and find the number between 1 to 6
b. Repeat the Die roll and find the result each time
c. Store the result in a dictionary
d. Repeat till any one of the number has reached 10 times
e. Find the number that reached maximum times and the one that was for minimum times
Answer:
-------
touch dice.sh
nano dice.sh
************
#!/bin/bash
declare -A dict
a=1;
b=1;
c=1;
d=1;
e=1;
f=1;
echo "Generated random numbers are:"
for i in range $(seq 50)
do
x=$(( 1+RANDOM%6 ))
if [[ x -eq 1 ]]
then
        a=$((a+1))
        echo "dict[$i]=$a"
        if [[ $a -eq 10 ]]
        then
                break;
        else
                continue;
        fi
fi

if [[ x -eq 2 ]]
then
        b=$((b+1))
         echo "dict[$i]=$b"
        if [[ $b -eq 10 ]]
        then
                break;
        else
                continue;
        fi
fi
if [[ x -eq 3 ]]
then
        c=$((c+1))
        echo "dict[$i]=$c"
        if [[ $c -eq 10 ]]
        then
                break;
        else
                continue;
        fi
fi

if [[ x -eq 4 ]]
then
        d=$((d+1))
        echo "dict[$i]=$d"
        if [[ $d -eq 10 ]]
        then
                break;
        else
                continue;
        fi
fi

if [[ x -eq 5 ]]
then
        e=$((e+1))
         echo "dict[$i]=$e"
        if [[ $e -eq 10 ]]
        then
                break;
        else
                continue;
        fi
fi
if [[ x -eq 6 ]]
then
        f=$((f+1))
         echo "dict[$i]=$f"
        if [[ $f -eq 10 ]]
        then
                break;
        else
                continue;
        fi
fi

done

echo "Dice with its total count here:"
echo "1=$a"
echo "2=$b"
echo "3=$c"
echo "4=$d"
echo "5=$e"
echo "6=$f"

arr=($a $b $c $d $e $f)
min=0
max=0

for i in ${arr[@]}; do
    (( $i > max || max == 0)) && max=$i
    (( $i < min || min == 0)) && min=$i
done

echo "Minimum value that is $min"
echo "Maximum value that is $max"
*********************
Output:
------
LENOVO@DESKTOP-2N2U3UA MINGW64 ~/Command/linux-content (master)
$ ./dice.sh
Generated random numbers are:
dict[range]=2
dict[1]=2
dict[2]=2
dict[3]=3
dict[4]=3
dict[5]=2
dict[6]=2
dict[7]=2
dict[8]=3
dict[9]=4
dict[10]=4
dict[11]=3
dict[12]=5
dict[13]=3
dict[14]=4
dict[15]=5
dict[16]=5
dict[17]=6
dict[18]=6
dict[19]=4
dict[20]=6
dict[21]=7
dict[22]=3
dict[23]=4
dict[24]=7
dict[25]=7
dict[26]=4
dict[27]=8
dict[28]=8
dict[29]=8
dict[30]=9
dict[31]=5
dict[32]=9
dict[33]=6
dict[34]=7
dict[35]=10
Dice with its total count here:
1=8
2=9
3=5
4=10
5=7
6=4
Minimum value that is 4
Maximum value that is 10

2)Write a Program to generate a birth month of 50 individuals between the year 92 & 93. Find all the individuals having birthdays in the same month.Store it to finally print.
Answer:
------
touch birth.sh
nano birth.sh
*************
declare -A dict
ja=0;
f=0;
m=0;
a=0;
ma=0;
j=0;
ju=0;
au=0;
s=0;
o=0;
n=0;
d=0;

jan=0;
feb=0;
mar=0
apr=0;
may=0;
june=0;
july=0;
aug=0;
sep=0;
oct=0;
nov=0;
dec=0;

for i in $(seq 50)
do
ar=$(($RANDOM%2))
mnth=$((+RANDOM%10+3))
if [[ $ar -eq 0 ]]
then
        year=1992;
        if [[ $mnth -eq 1 ]]
        then
                echo "$i person birthday  = January $year"
                jan=$((jan+1))
                continue
        fi
 if [[ $mnth -eq 2 ]]
        then
                echo "$i person birthday  = February $year"
                feb=$((feb+1))
                continue
        fi

        if [[ $mnth -eq 3 ]]
        then
                echo "dict[$i] person birthday  = March $year"
                mar=$((mar+1))
                continue
        fi
        if [[ $mnth -eq 4 ]]
        then
                echo "dict[$i] person birthday  = April $year"
                apr=$((apr+1))
                continue
        fi
        if [[ $mnth -eq 5 ]]
        then
                echo "dict[$i] person birthday  = May $year"
                may=$((may+1))
                continue
        fi
        if [[ $mnth -eq 6 ]]
        then
                echo "dict[$i] person birthday  = June $year"
                june=$((june+1))
                continue
        fi
        if [[ $mnth -eq 7 ]]
        then
                echo "dict[$i] person birthday  = July $year"
                july=$((july+1))
                continue
        fi
        if [[ $mnth -eq 8 ]]
        then
                echo "dict[$i] person birthday  = August $year"
                aug=$((aug+1))
                continue
        fi
if [[ $mnth -eq 9 ]]
        then
                echo "dict[$i] person birthday  = September $year"
                sep=$((sep+1))
                continue
        fi
        if [[ $mnth -eq 10 ]]
        then
                echo "dict[$i] person birthday  = October $year"
                oct=$((oct+1))
                continue
        fi
        if [[ $mnth -eq 11 ]]
        then
                echo "dict[$i] person birthday  = November $year"
                nov=$((nov+1))
                continue
        fi
        if [[ $mnth -eq 12 ]]
        then
                echo "dict[$i] person birthday  = December $year"
                dec=$((dec+1))
                continue
        fi


else
        year=1993;
        if [[ $mnth -eq 1 ]]
        then
                echo "dict[$i] person birthday = January $year"
                ja=$((ja+1))
                continue
        fi
        if [[ $mnth -eq 2 ]]
        then
                echo "dict[$i] person birthday  = February $year"
                f=$((f+1))
                continue
        fi

        if [[ $mnth -eq 3 ]]
        then
                echo "dict[$i] person birthday  = March $year"
                m=$((m+1))
                continue
        fi
        if [[ $mnth -eq 4 ]]
        then
                echo "dict[$i] person birthday  = April $year"
                a=$((a+1))
                continue
        fi
        if [[ $mnth -eq 5 ]]
        then
                echo "dict[$i] person birthday  = May $year"
                ma=$((ma+1))
                continue
        fi
        if [[ $mnth -eq 6 ]]
        then
                echo "dict[$i] person birthday  = June $year"
                j=$((j+1))
                continue
        fi
         if [[ $mnth -eq 7 ]]
        then
                echo "dict[$i] person birthday  = July $year"
                ju=$((ju+1))
                continue
        fi
        if [[ $mnth -eq 8 ]]
        then
                echo "dict[$i] person birthday  = August $year"
                au=$((au+1))
                continue
        fi
        if [[ $mnth -eq 9 ]]
        then
                echo "dict[$i] person birthday  = September $year"
                s=$((s+1))
                continue
        fi
 if [[ $mnth -eq 10 ]]
        then
                echo "dict[$i] person birthday  = October $year"
                o=$((o+1))
                continue
        fi
        if [[ $mnth -eq 11 ]]
        then
                echo "dict[$i] person birthday  = November $year"
                n=$((n+1))
                continue
        fi
        if [[ $mnth -eq 12 ]]
        then
                echo "dict[$i] person birthday  = December $year"
                d=$((d+1))
                continue
        fi

fi
done

echo "-----------------------------------------"

echo "BIRTHDAY LIST OF INDIVISUALS IN THE YEAR OF 1992 "
echo "January =$jan"
echo "February =$feb"
echo "March=$mar"
echo "April=$apr"
echo "May=$may"
echo "June=$june"
echo "July=$july"
echo "August=$aug"
echo "September=$sep"
echo "October=$oct"
echo "November=$nov"
echo "December=$dec"
echo "-------------------------------------------"
echo "BIRTHDAY LIST OF INDIVISUALS IN THE YEAR OF 1993"
echo "January =$ja"
echo "February =$f"
echo "March=$m"
echo "April=$a"
echo "May=$ma"
echo "June=$j"
echo "July=$ju"
echo "August=$au"
echo "September=$s"
echo "October=$o"
echo "November=$n"
echo "December=$d"
echo "-------------------------------------------"

*************
Output:
-------
$ ./birth.sh
dict[1] person birthday  = October 1992
dict[2] person birthday  = July 1992
dict[3] person birthday  = March 1993
dict[4] person birthday  = June 1992
dict[5] person birthday  = December 1993
dict[6] person birthday  = May 1992
dict[7] person birthday  = May 1992
dict[8] person birthday  = June 1992
dict[9] person birthday  = May 1993
dict[10] person birthday  = July 1993
dict[11] person birthday  = November 1993
dict[12] person birthday  = September 1992
dict[13] person birthday  = April 1992
dict[14] person birthday  = July 1992
dict[15] person birthday  = March 1993
dict[16] person birthday  = December 1993
dict[17] person birthday  = October 1992
dict[18] person birthday  = November 1993
dict[19] person birthday  = September 1993
dict[20] person birthday  = August 1992
dict[21] person birthday  = July 1992
dict[22] person birthday  = August 1993
dict[23] person birthday  = October 1992
dict[24] person birthday  = March 1992
dict[25] person birthday  = May 1992
dict[26] person birthday  = October 1992
dict[27] person birthday  = April 1993
dict[28] person birthday  = April 1992
dict[29] person birthday  = April 1993
dict[30] person birthday  = April 1992
dict[31] person birthday  = April 1992
dict[32] person birthday  = June 1992
dict[33] person birthday  = April 1992
dict[34] person birthday  = April 1993
dict[35] person birthday  = May 1992
dict[36] person birthday  = August 1993
dict[37] person birthday  = March 1993
dict[38] person birthday  = April 1992
dict[39] person birthday  = October 1992
dict[40] person birthday  = November 1992
dict[41] person birthday  = April 1992
dict[42] person birthday  = May 1993
dict[43] person birthday  = April 1993
dict[44] person birthday  = March 1992
dict[45] person birthday  = August 1992
dict[46] person birthday  = August 1993
dict[47] person birthday  = June 1992
dict[48] person birthday  = April 1993
dict[49] person birthday  = October 1992
dict[50] person birthday  = September 1992
-----------------------------------------
BIRTHDAY LIST OF INDIVISUALS IN THE YEAR OF 1992
January =0
February =0
March=3
April=1
May=5
June=2
July=3
August=3
September=0
October=1
November=3
December=3
-------------------------------------------
BIRTHDAY LIST OF INDIVISUALS IN THE YEAR OF 1993
January =0
February =0
March=3
April=1
May=4
June=2
July=2
August=2
September=1
October=4
November=6
December=1
----------------------------------------------------
***************************************END**********************************
