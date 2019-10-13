# dial
Each number on telephone keypads, except 0 and 1, corresponds to a set of uppercase letters as shown in this list: 2 ABC, 3 DEF, 4 GHI, 5 JKL, 6 MNO, 7 PQRS, 8 TUV, 9 WXYZ. Hence, a phone-number specification can include uppercase letters and digits. The function takes as its input argument a character array of length 16 or less that includes only these characters and returns as its output argument the telephone number as a uint64. The phone number must never start with 0. If the input contains any illegal characters, the function returns 0.

Example run:
>> out=dial('1FUNDOG4YOU')
out =
 uint64
  13863644968
