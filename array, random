
float [] x,y;
void setup(){
  size(1600,800);
  x = new float[8];
  y = new float[8];
  for(int i=0;i<4; i++){
    x[i] = 50+50*i;
    y[i] = height/2 - 30;
    x[i+4] = 50+50*i;
    y[i+4] = height/2 + 30;  
  }
}
void draw(){
  background(255,255,0);
  for(int i=0;i<8; i++){
{  
  float d;
  d = random(100,200);
  smile(x[i], y[i], d);
  x[i] += 15;
  if(x[i]>width) x[i] = 0;
}
  
  } 
}
void smile(float a, float b, float g){
  fill(255,0,255);
  circle(a,b,g);
  circle(a-10,b-10,20);
  circle(a+10,b-10,20);
}
