#kill
این کامند برعکس اسمش اصلا به معنی کشتن نیست 
در حقیقت یه sender signal هستش 
دلیلش اینه به خاطر که مستقیم نمیتونیم بگیم یه پروسه از بین بره یا باشه این کامند میشه گفت کامند سطح پایین در سطح کرنل هستش چون به برنامه یسری سیگنال میفرسته یه کاری انجام بده 
برای دیدن سیگنال ها 
```bash
kill -l
```

البته به صورت یسری کامند هستش 
```bash
kill -l
HUP INT QUIT ILL TRAP IOT BUS FPE KILL USR1 SEGV USR2 PIPE ALRM TERM STKFLT CHLD CONT STOP TSTP TTIN TTOU URG XCPU XFSZ VTALRM PROF WINCH POLL PWR SYS
```
مثلا اینطوری برات نمایش میده 
