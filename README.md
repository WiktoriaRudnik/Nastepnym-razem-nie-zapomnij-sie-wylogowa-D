A
import matplotlib.pyplot as plt
import pandas as pd
import random
import numpy as np
import math
import seaborn as sns

plt.plot((np.arange(-20,20,0.1)),(np.sin(np.arange(-20,20,0.1))))
plt.plot((np.arange(-20,20,0.1)),(np.cos(np.arange(-20,20,0.1))))
plt.xticks(np.arange(-20,20,10))
plt.legend(labels=['cos', 'sin'],loc="best")
plt.show()

# xlsx = pd.read_csv('flag.csv',header=0,sep=",",decimal='.')
# df = pd.DataFrame(xlsx)
# aaa = pd.DataFrame(xlsx)
# # print(df)
# # df2 = df[-75:]
# # print(df2)
# # a = df2.groupby(['religion']).agg({'population':['sum']})
# # a.plot(kind='bar',rot=45,figsize=(8, 8))
# # plt.ylabel('Ilość')
# # plt.xlabel("wiara")
# # plt.title('Wykres')
# # plt.legend(labels=[])
# # plt.show()
# # plt.savefig('Wykresik.png')
#
#
# b = df[['religion','landmass']].groupby(['religion']).agg({'landmass':['sum']})
# print(b)
# b.plot(kind='pie',subplots=True,autopct='%.2f %%',figsize=(10, 10),fontsize=14)
# plt.title('Tytuł')
# plt.legend(loc=0)
# plt.show()
# # df2 = df3 = df[-75:]
# # df2 = df2['area']
# # df3 = df3['population']
# # sns.set()
# # print(df2)
# # data = {'a': df2,
# #         'b': np.random.randint(25, 200, 75),
# #         'c': df3}
# # print(data['b'])
# # df = pd.DataFrame(data)
# # plot = sns.relplot(data=df, x="a", y="b", hue="c",
# # palette='muted')
# # plot.fig.set_size_inches(10, 10)
# # plt.show()
Zad 1. (6pkt.) Za pomocą bibliotek matplotlib utwórz wykres liniowy funkcji 𝑓(𝑥)= 𝑥2+4 2𝑥 dla liczb całkowitych x z przedziału od [0,10). Dodaj odpowiednie etykiety do osi wykresu, tytuł linii oraz tytuł wykresu. Ustaw zakres na osi x na graniczne wartości z przedziału. Wyświetl legendę.
Zad 2. (10pkt.) Za pomocą matplotlib odwzoruj siatkę wykresów z poniższego zdjęcia. Siatkę zapisz do pliku(imie_nazwisko_zad2.png)
Zad 3. (6pkt) Używając biblioteki pandas wczytaj zawartość pliku „automobile.csv” do ramki danych i wykonaj następujące kroki:
• Ze 100 wierszy wybranych losowo bez powtarzania utwórz nową ramkę danych
• Na nowej ramce danych dokonaj grupowania danych po kolumnie ‘Car model’
• Na wykresie kołowym przedstaw wielkości poszczególnych grup, wartości liczbowe na wykresie mają być zaokrąglone bez części dziesiętnych, ustaw czcionkę rozmiaru 14, dodaj etykietę do wykresu oraz tytuł.
Zad 4. (8pkt.)
Za pomocą biblioteki pandas wczytaj zawartość pliku „automobile.csv”, następnie utworzysz grupę po kolumnie „Car model” i policzysz średnią cenę samochodów dla każdej z marek (kolumna Price), dane zobrazujesz na wykresie słupkowym, do stworzenia wykresu wykorzystaj bibliotekę matplotlib. Dodaj etykiety do osi wykresu oraz tytuł.
Uwaga: wszystkie wykresy mają być widoczne w całości, czyli każdy element wykresu musi być widoczny. Wektory do zadań 1 i 2 robione za pomocą biblioteki numpy.
