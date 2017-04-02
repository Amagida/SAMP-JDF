# SAMP-JDF
an include that can help you to convert gregorian to jalali or jalali to gregorian.

# Example Usage
```
    new jy, jm, jd;
    gregorian_to_jalali(2016, 10, 7, jy, jm, jd);
    printf("%d/%d/%d", jy, jm, jd); //Will return: 1395/7/16
    __________________________________________________________
    new gy, gm, gd;
    jalali_to_gregorian(1395, 7, 16, gy, gm, gd);
    printf("%d/%d/%d", gy, gm, gd); //Will return: 2016/10/7
    __________________________________________________________
    new y, m, d;
    getjdate(y, m, d);
    printf("%d/%d/%d", y, m, d); //Will return currect Jalali date
```
