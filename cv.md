# Dmitry Vavilin

## Contacts:

- **E-mail:** vdmitry08@gmail.com
- **Discord:** monte_v

## About myself:

I am a fourth-year student of SFPGU. Having a lot of free time, I want to do something, upgrade my skills. Web site layout has always been a "dark forest" for me, so the choice fell on it. And I hope I don't give up.

## Skills:

   - Python
   - SQL
   - HTML&CSS (basic)
   - JS (basic)
   - PHP (basic)
   - C# (basic)

## Code example:

```python
def insert_sort(arr):
   for item in range(1, len(arr)):
      k = item
      while k > 0 and arr[k-1] > arr[k]:
         arr[k], arr[k-1] = arr[k-1], arr[k]
         k -= 1

def test_sort(algorithm):
   print('Test')
   arr = [5, 2, 4, 1, 3]
   print(arr, end='\n-------------------------\n')
   result = algorithm(arr)
   print('Test passed successfully' if arr.sort() == result else 'test failed')

if __name__ == "__main__":
   test_sort(insert_sort)
```

## Education:

SFPGU, specialization - technician programmer

## Languages:

- Russian - Native
- English - A1
