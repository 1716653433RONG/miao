
<script type="x" id="ch0105/1">
    var n = Number (prompt())
    var allAge = 0
    for (var i = 0;i<n;i++){
        var age = Number(prompt())
        allAge += age 
    }
    {
        console.log((allAge/n).toFixed(2))
    }
</script>

<script type="x" id="ch0105/2">
    var allMoney = 0
for (var i = 0;i <= 12;i++){
    var money = Number(prompt())
    allMoney  += money
} {
    console.log("$" + (allMoney/12).toFixed(2))
    }
</script>

<script type="x" id="ch0105/3">
var n = +prompt()
var a = 0
var x = 0
for (var i =0;i<n;i++){
    var a = Number(prompt())
    x += a 
}{
    console.log((x/n).toFixed(4))
}
</script>

<script type="x" id="ch0105/4">
var n = Number(prompt())
var a = 0
var b = 0
for (var i=1;i<n;i++){
var b = Number(prompt())

}
    console.log(n(n+1)/2)    
</script>

<script type="x" id="ch0105/5">
var n = Number(prompt())
for (var i = 0;i<n;i++)
var b = Number(prompt())
if (b>max){
    b = max
}
    console.log(max)
</script>

<script type="x" id="ch0105/6"> 
min = 9999 , max = 0
var n = Number(prompt())
for (var i = 1;i<=n;i++)
var b = Number(prompt())
if (max<b){
    max = b
}
if (min>b){
    min=b
} 
{
    console.log(max - min)
}
</script>

<script type="x" id="ch0105/7">
var n = +prompt()
var sumj = 0
var sumy = 0
var sumt = 0
for (var i = 0;i<n;i++)
{   var j = +prompt()
    var y = +prompt()
    var t = +prompt()
    sumj += j
    sumy += y
    sumt += t
}
console.log(j,y,t ,(j+y+t))
</script>


<script type="x" id="ch0105/8">
var n = +prompt()
var a = +prompt()
var b = +prompt()
for (var i = 1 ;i < (n-1); i++ )
{
    b += a
} 
    console.log((n-2)*180-b)
</script>


<script type="x" id="ch0105/9">
var n = +prompt()
var m = +prompt()
var sum = 0
for (var i = n ; i<= m ; i++)
{
    if (i % 2 ==1)
        sum += i
}
    console.log(sum)
</script>


<script type="x" id="ch0105/10">
var m = +prompt()
var n = +prompt()
var sum = 0
for (var i = m;i<=n;i+=17)
{
    if(i % 17 == 0)
    sum += i
}
    console.log(sum)
</script>

<script type="x" id="ch0105/11">
var k = +prompt()
var a1 = 0
var a5 = 0
var a10 = 0
for (var i=0;i<k;i++)
var x = +prompt()
   if(x=1){
    a1++;
}
    if(x=5){
    a5++;
}
    if(x=10){
    a10++;
}
console.log(a1,a5,a10)
</script>

<script type="x" id="ch0105/12">
var n = +prompt()
var m = +prompt()
for (i =0;i<n;i++)
var x = +prompt()
if (x==m)
{
    x++
}
console.log(x)
</script>


<script type="x" id="ch0105/13">
var a = prompt()
var n = prompt()
var x = 1
for (i = 0;i<n;i++){
    x = x*a
}
console.log(x)
</script>

<script type="x" id="ch0105/14">
var x = +prompt()
var n = +prompt()
for (i=0;i<n;i++){
    x= x * 1.001
}
console.log(x.toFixed(4))
</script>

<script type="x" id="ch0105/15">
var r = +prompt()
var m = +prompt()
var y = +prompt()
var x = 1 + r/100
for (i=0;i<y;i++){
    m = m*x
}
console.log(m|0)
</script>

<script type="x" id="ch0105/17">
var k = +prompt()
var a = 1
var b = 1
var c = 0
for (i=0;i<k;i++){
    c=a+b
    a=b
    b=c
}
console.log(c)
</script>

<script>
    var n = +prompt()
    var baseTotal = +prompt()
    var baseEffect = +prompt()
    var baseRatio = baseEffect/baseTotal
for (var i = 0;i<n;i++)
    var total = +prompt()
    var effect = +prompt()
    var ratio = effect/total
if(ratio-baseRatio>0.5){
    console.log("better")
} if (ratio-baseRatio<0.5){
    console.log("worse")
}if (ratio-baseRatio == 0.5){
    console.log("same")
}
</script>
