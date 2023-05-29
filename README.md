# Poisa_face_blur
zad.1. Może zostać z  tym zaznaczaniem.(1pkt)

zad.2. Otwórz skrypt 'face_detection-blur.py', następnie w lini 65 kodu, zmieniaj wartość warunku 'if confidence >= 0.4'.

	a) co się dzieje po zwiększeniu a co po zmniejszeniu wartości.(1pkt)
	b) jaka jest optymalna wartość.(1pkt)

zad.3. Korzystając z wartości wybranej w poprzednim zadaniu,sprawdź który model najlepiej wykrywa twarze. Model znajdują się w katalogu 'models', ich zmiany możesz dokonać poprzez zmianę nazwy w nawiasie w lini 8. (1pkt)

zad.4. Używając tego samego skryptu co w zadaniu porzednim odkomentuj linie 148-150 a następnie dobierz współczynnik blur_ratio znajdujący się w lini 125, tak aby twarze były prawidłowo zamazane.Współczynik ten przyjmuje wartości od 0 do 100.(1pkt).

zad.5. Cały czas używając tego samego skryptu sparwdź jego działanie na 4 różnych wideo - znajdują się one w katalogu 'videos', a ich zmiany w skrypcie możesz dokonać poprzez zmianę nazwy w lini 25 skryptu. (1pkt)

zad.6. Otwórz skrypt 'face_detection_frames.py'. Odpowiada on za blurowanie kilku klatek wstecz lub do przodu po wykryciu obiektu. -nie wiem jak to inaczej napisać żeby działało

	a) podaj linie w której zaczyna się kod odpowiedzialny za blurowanie kaltek wstecz oraz do przodu.(0.5pkt)
	
	b) Sprawdź ile klatek do przodu lub tyłu najlepiej się sprawdza. Podczas testowania jedna z pętli (klatki w tył lub klatki w przód) powinna być zakomentowana. Zmiane liczby klatek możesz dokonać w lini 127. (0.5pkt)
	
	c) Sprawdź która z opcji działa lepiej dla wideo:people_walking, a która dla wideo: people_walking_in_park. Przy wcześniej wybranej liczbie klatek.(1pkt)
	
zad.7. Otwórz skrypt 'face_detection_average.py, zmieniając liczbę kaltek do uśrednienia w lini 127. Opisz co powoduje zmiana klatek. (1pkt)
