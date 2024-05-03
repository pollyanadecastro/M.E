#include <iostream>
#include <bitset>
#include "emojis/emoji.h"
using namespace std;

int main() {
  int num;
  cout << "Insira um número: ";
  cin >> num;
  
  string binario = bitset<sizeof(int) * 8>(num).to_string();

  string emoji;
  if (binario.back() == '1') {
      emoji = emojicpp::emojize(":smile:"); 
  } else {
      emoji = emojicpp::emojize(":chocolate_bar: "); 
  }

  cout << "Em binário: " << binario << " " << emoji << endl;

  return 0;

}
