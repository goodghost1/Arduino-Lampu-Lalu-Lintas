# Arduino-Lampu-Lalu-Lintas
int lampuMerah  = 7; //Lampu LED Merah
int lampuKuning = 6; //Lampu LED Kuning
int lampuHijau  = 5; //Lampu LED Hijau
 
void setup() {
  pinMode(lampuMerah, OUTPUT);
  pinMode(lampuKuning, OUTPUT);
  pinMode(lampuHijau, OUTPUT);
}
 
void loop() {
  //Lampu Merah menyala selama 3 detik
  digitalWrite(lampuMerah, HIGH);
  delay(3000); // jeda selama 3 detik
  digitalWrite(lampuMerah, LOW);
 
  //Lampu Kuning menyala selama 2 detik
  digitalWrite(lampuKuning, HIGH);
  delay(2000); //jeda selama 2 detik
  digitalWrite(lampuKuning, LOW);
 
  //Lampu Hijau menyala selama 5 detik
  digitalWrite(lampuHijau, HIGH);
  delay(5000); //jeda selama 5 detik
  digitalWrite(lampuHijau, LOW);
}
 
