# teenSum
public int teenSum(int a, int b) {
  int sum = a + b;
  
  if((a > 12 && a < 20) || (b > 12 && b < 20)){
    return 19;
  }
  return sum;
}
