# Überschrift 1

## Überschrift 2

```python
def division(num1, num2):
    try:                         # nur ausführen, wenn kein Fehler auftritt (probiere es aus)
    
        result = int(num1) / int(num2)
        print(f"{num1} divided by {num2} is {result}")
    except ZeroDivisionError:   # nur ausführen, wenn ein ZeroDivisionError auftritt (Division durch 0)
        print("Error: \n    Cannot divide by zero")
    except ValueError:          # nur ausführen, wenn ein ValueError auftritt (keine Zahl eingegeben)
        print("Error: \n    Please enter a number")
    except:                     # nur ausführen, wenn ein anderer Fehler auftritt
        print("Something went wrong")
    finally:                    # immer ausführen (egal ob Fehler aufgetreten ist oder nicht) am Ende
        print("\nDivision operation completed")
num1 = input("Enter a number: ")
num2 = input("Enter another number: ")
print("\nDivision operation started\n")
division(num1, num2)
```

* Beschreibung:

In diesem Code passiert

1. das
2. dies
3. jenes
4.
