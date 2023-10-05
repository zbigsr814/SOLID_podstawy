S - W folderze Invoice każda poszczególna klasa odpowiada za jedną funkcję. LineItem odpowiada za agregację danych. Występuje loggowanie danych do konsoli i do pliku pdf.
O - W folderze module występuję klasy otwarte na rozszerzenia. Wykorzystano przeciążenie metody Render w klasach Circle i Rectangle.
L - Zastosowano klasę abstrakcyjną Duck, która następnie jest dziedziczona przez klasy pochodne. Klasy pochodne rozszerzają właściwości klasy bazowej.
I - W pliku IPrinter rozbito cztery metody na trzy interfejsy.
D - Klasa bazowa AuthenticationManager oddzielona jest przez interfejsy od klas wykonawczych Sms/EmailSender