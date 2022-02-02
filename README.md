# assignment2-reddy
# vamsidhar reddy
###### HyderabadHouse. 
Near by the HyderabadHouse, many **Indians** reside, and many other **Indian restaurants** too.</br> 
This restaurant is owned by an Indian and is located in **Chicago, IL**.

*** 

### Airport to HyderabadHouse
O'Hare is the international airport that is near to HyderabadHouse
1. from airport take a cab to rosephalt
2. from rosephalt take pace bus to schaumburg pace station 
3. take a walk for 350 meters W to reach HyderabadHouse

***
The food that must try by others :</br>
*Chicken Tikka Masala

*Chicken Butter Masala  

*chicken Lollipos</br>
[About me](AboutMe.md)

***

## Sports Activities

#### The below table shows the sports which are located at various locations and the amount to be charged for participation.

| Name | Location | Amount |
| --- | --- | --- |
| Badminton | Recreation center | 10 |
| Cricket | Indore | 11 |
| TableTennis | Colden Hall | 14 |
| BasketBall | Valk Center | 15 |

***

## Quotes
> "I slept and dreamt that life was joy. I awoke and saw that life was service. I acted and behold, service was joy".</br>
 >>  -*Rabindranath Tagore*</br>
> To succeed in your mission, you must have single-minded devotion to your goal.</br>
>>   -*A. P. J. Abdul Kalam*</br>
***
### Code fencing

> An ancient method which appeared about 200 BC in Pingala's Hindu classic Chandah-sutra (and now called left-to-right binary exponentiation) can be described as follows. First write the exponent 25 in binary: 11001. Remove the first binary digit leaving 1001 and then replace each remaining '1' with the pair of letters 'sx' and each '0' with the letter 's' to get: sx s s sx. Now interpret 's' to mean square, and 'x' to mean multiply by x, so we have:

square, multiply by x, square, square, square, multiply by x.
[description](https://primes.utm.edu/glossary/page.php?sort=BinaryExponentiation)

'''

long long binpow(long long a, long long b) {</br>
    if (b == 0)</br>
        return 1;</br>
    long long res = binpow(a, b / 2);</br>
    if (b % 2)</br>
        return res * res * a;</br>
    else</br>
        return res * res;</br>
}</br>

'''
[description](https://cp-algorithms.com/algebra/binary-exp.html)
