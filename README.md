1. Introduction
2. Variables
3. Functions
4. Object and Data Structures
5. Classes
6. SOLID
7. Testing
8. Concurrency
9. Error Handling
10. Formatting
11. Comments
12. Translation

INTRODUCTION

VARIABLES
- Use meaningful names
Variables' names should display its (unique) characteristic

Bad naming:

```
{
  function exponentiation(int a1, int a2) {
    return pow(a1, a2);
  }
}    
```

Good naming:

```
{
  function exponentiation( int BaseOperand; int ExponentOperand){
    return pow(BaseOperand, ExponentOperand);
  }
}
```

- Use pronounceable names

Bad naming:

```
{
  function expo(int BsOpr, int ExpOpr) {
    return pow(BsOpr, ExpOpr);
  }
}
```  

Good naming:

```
{
  function exponentiation( int BaseOperand; int ExponentOperand) {
    return pow(BaseOperand, ExponentOperand);
  }
}
```

- Use the same vocabulary for the same type of variables:

Bad naming

```
{
  function exponentiation( int FirstOperand; int Exponent) {
    return pow(FirstOperand, Exponent);
  }
}
```

Good naming:

```
{
  function exponentiation( int BaseOperand; int ExponentOperand) {
    return pow(BaseOperand, ExponentOperand);
  }
}
```

- Use name easy for searching;

Bad naming:

```
{
  SetBit(0x1000); //WTF is '0x1000'??
}
```

Good naming:

```
{
  #define GPIO_PIN_12 ((uint16_t)0x1000);
  SetBit(GPIO_PIN_12);
}
```
