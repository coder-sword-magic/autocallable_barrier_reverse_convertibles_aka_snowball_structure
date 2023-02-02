# Autocallable Barrier Reverse Convertibles
calculate value and greeks of autocallable barrier reverse convertibles (aka snowball structure contract) using monte carlo implementing by vectorized functions.

## The product / contract info:
* Start Date: 2022-08-31
* End Date: 2023-08-31
* Initial Underlying Price: 3000
* Coupon Rate:  20%
* Knock In Ratio: 80%
* Knock Out Calendar:

   | no | knock out monitor | knock out price | knock out ratio | 
   | -- | ----------------- | --------------- | --------------- | 
   | 1  | 20220928 | 3000 | 1.0 |
   | 2  | 20221031 | 2985 | 0.995 |
   | 3  | 20221130 | 2970 | 0.99  |
   | 4  | 20230104 | 2955 | 0.985 |
   | 5  | 20230131 | 2940 | 0.98  |
   | 6  | 20230228 | 2925 | 0.975 |
   | 7  | 20230331 | 2910 | 0.97  |
   | 8  | 20230505 | 2895 | 0.965 |
   | 9  | 20230531 | 2880 | 0.96  |
   | 10 | 20230630 | 2865 | 0.955 |
   | 11 | 20230731 | 2850 | 0.95  |
   | 12 | 20230831 | 2835 | 0.945 |
   
   

- - -

If you have any question about this repo, do not hesitate to contact me or open an issue on GitHub.

