#include "FIFO.h"

char data[] = "Hola Mundo!!!!";
fifo_t myfifo;

void setup() {
  Serial.begin(115200);
  while (!Serial);
