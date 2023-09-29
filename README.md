def subtraktionsrechner(num1, num2):
    ergebnis = num1 - num2
    return ergebnis

# Benutzerinteraktion
try:
    num1 = float(input("Geben Sie die erste Zahl ein: "))
    num2 = float(input("Geben Sie die zweite Zahl ein: "))
    
    ergebnis = subtraktionsrechner(num1, num2)
    
    print(f"Das Ergebnis der Subtraktion von {num1} und {num2} ist {ergebnis}")
except ValueError:
    print("Ungültige Eingabe. Bitte geben Sie gültige Zahlen ein.")
    

    
