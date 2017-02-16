### Pengunaan .env
```
npm install --save dotenv
```
simpan variabel pada file '.env'
```
consumer_key    = uKZP166jkMLVc15m0lHY8kGMT
consumer_secret = d3eaGtnGs3l6OUq3P2EF0Qe1r8D2hVOt1VM8HSRBeDNkDvNqI8
```
sertakan require pada setiap page penggunaan
```
require('dotenv').config()
```

penggunaannya adalah seeperti berikut
```
data_key    : process.env.consumer_key,
data_secret : process.env.consumer_secret,
```
