# Poisa_face_blur
zad.1. Może zostać z  tym zaznaczaniem.(1pkt)

zad.2. Otwórz skrypt 'face_detection-blur.py', następnie w lini 65 kodu, zmieniaj wartość warunku 'if confidence >= 0.4'(przedział wartości jakie można ustawić to 0-1).

	a) co się dzieje po zwiększeniu a co po zmniejszeniu wartości.(1pkt)
	b) jaka jest optymalna wartość.(1pkt)

zad.3. Korzystając z wartości wybranej w poprzednim zadaniu,sprawdź który model najlepiej wykrywa twarze. Model znajdują się w katalogu 'models', ich zmiany możesz dokonać poprzez zmianę nazwy w nawiasie w lini 8. (1pkt)

zad.4. Używając tego samego skryptu co w zadaniu porzednim odkomentuj linie 148-150 a następnie dobierz współczynnik blur_ratio znajdujący się w lini 125, tak aby twarze były prawidłowo zamazane.Współczynik ten przyjmuje wartości od 0 do 100.(1pkt).

zad.5. Cały czas używając tego samego skryptu sparwdź jego działanie na 4 różnych wideo - znajdują się one w katalogu 'videos', a ich zmiany w skrypcie możesz dokonać poprzez zmianę nazwy w lini 25 skryptu. Dla którego wideo jest otrzymywany najlepszy efekt?(1pkt)

zad.6. Otwórz skrypt 'face_detection_frames.py'. Odpowiada on za cofnięcie się kilka kaltek do tyłu po wykryciu obiektu, a następnie bluruje te poprzednie kaltki. -działa tylko nie usuwa tych cofniętych klatek.

	a) podaj linie w której zaczyna się kod odpowiedzialny za blurowanie klatek wstecz.(0.5pkt)
	
	b) Sprawdź ile klatek do tyłu najlepiej się sprawdza. Zmiane liczby klatek możesz dokonać w lini 123. (1pkt)
	
	c) Jaki pojawia się problem w przetworzonym wideo, oraz jak można byłoby go naprawić? (0.5pkt)
	
zad.7. Otwórz skrypt 'face_detection_average.py', zmieniając liczbę kaltek do uśrednienia w lini 127. Opisz co powoduje zmiana klatek. (1pkt)

Wnioski(1pkt)
