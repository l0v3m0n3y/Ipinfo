# Ipinfo
JavaScript library for ipinfo.io
# main
```js
async function main(){
    const {ipinfo} = require('./ipinfo');
    const info= new ipinfo();
    let req=await info.my_ip()
    console.log(req)
}
main()
```
