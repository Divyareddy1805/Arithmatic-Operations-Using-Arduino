# Arithmatic-Operations-Using-Arduino
Arithematic operations are ways of combining, transforming,or manipulating numbers.They are functions that have number both as input and output.The most important operations in arithmatic are addition,subtraction,multiplication,and division.r
void setup() {
  // put your setup code here, to run once:
Serial.begin(9600);
int a,b,c,d,e,f,g;
a=5,b=7;
c=a+b;
d=a-b;
e=a*b;
f=a/b;
g=a&b;
Serial.println(c);
Serial.println(d);
Serial.println(e);
Serial.println(f);
Serial.println(g);
}

void loop() {
  // put your main code here, to run repeatedly:

}
