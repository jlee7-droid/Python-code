// Clears the trigPin
  digitalWrite(trigPin, LOW);
  delayMicroseconds(2);
// Sets the trigPin on HIGH for 10 micro seconds
  digitalWrite(trigPin, HIGH);
  delayMicroseconds(10);
  digitalWrite(trigPin, LOW);
// Reads echoPin, returns the sound wave time in uS
  duration = pulseIn(echoPin, HIGH);
// Calculating the distance
  distance = duration * 0.034 / 2;
