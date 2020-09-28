int sensorPin = A0; 
float pot = 0.0; 
int n_leds = 5;
void setup() {
  for (int ii=0;ii<n_leds;ii++){
    pinMode(ii,OUTPUT); }
}
void loop() {
  pot = analogRead(sensorPin)/1023.0;
  if (int(3*n_leds*pot)==0){
  } else {
    for (int ii=0; ii<=int(n_leds*pot); ii++){
      digitalWrite(ii,HIGH);    }   
      }
  for (int jj=int(n_leds*pot); jj<14; jj++){
    digitalWrite(jj,LOW);  }
}
