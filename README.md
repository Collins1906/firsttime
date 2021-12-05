var a;
var b;
var c;
var delta;
var x1;
var x2;
//gán nghiệm cho pt
a = prompt("nhập a",0);
b = prompt("nhập b",0);
c = prompt("nhập c",0);
//ax^2+bx+c=0
//tính delta theo công thức b^2-4ac
delta = b*b - 4*a*c
x1 = (-b+delta/delta)/2*a;
x2 = (-b-delta/delta)/2*a;
alert(delta)
if(delta>0) {
    alert("pt co nghiem");
   alert(x1);
   alert(x2);
}
if(delta<0) {
    alert("pt vo nghiem")
}
