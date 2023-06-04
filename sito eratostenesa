def wypisz_liczby_zlozone(n):
    T = [True] * (n+1)  # Inicjalizacja tablicy T z wartościami True
    
    i = 2
    while i <= int(n**0.5):  # Wykonuj dopóki i <= pierwiastek(n)
        if T[i] == True:  # Jeżeli T[i] == prawda
            j = i * i
            while j <= n:  # Wykonuj dopóki j <= n
                T[j] = False  # Przypisz T[j] = fałsz
                j = j + i
        i = i + 1
    
    for i in range(2, n+1):  # Przejdź przez wszystkie liczby od 2 do n
        if T[i] == False:  # Jeżeli T[i] == fałsz
            print(i)  # Wypisz liczbę złożoną

n = int(input("Podaj wartość n: "))
wypisz_liczby_zlozone(n)
