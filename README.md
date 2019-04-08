# โปรแกรมพิมพ์บาร์โค้ด TSC

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

### วิธีการติดตั้ง

Copy TscActiveX.dll และ TSCLIB.dll ไปไว้ที่ Path

```sh
64Bit => C:\Windows\SysWOW64
32Bit => C:\Windows\System32
```

จากนั้นเปิด CMD ในโหมด Administrator แล้วพิมพ์คำสั่งต่อไปนี้

```sh
64Bit => C:\Windows\SysWOW64\regsvr32 C:\Windows\SysWOW64\TscActiveX.dll
32Bit => C:\Windows\System32\regsvr32 C:\Windows\System32\TscActiveX.dll
```

จากนั้นทำการ Restart 1 ครั้ง แล้วลองสั่งพิมพ์ ควรจะทำงานได้