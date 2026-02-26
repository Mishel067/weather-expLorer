# weather-expLorer
Command-line weather explorer for Russia's regional centres. Features: district grouping, coordinate database, logging, and clean CLI UX. Powered by Python &amp; Open-Meteo.
[README.md](https://github.com/user-attachments/files/25567590/README.md)
 # Weather Explorer
*A simple tool to check weather in Russian federal cities - by Misha(12 y.o.)*

## Whats it does
- Lets you choose a **federal district** (e.g. *Central*, *Siberian*),
- Then pick a city from that district,
- Fetched real-time weatger via [Open-Meteo API](https://open-meteo.com),
- Saves every request to `weather_log.txt`,

> No API keys needed
> Works in Google Colab or locally
> Built with Python, requests, datetime

## How to Run (in Google Colab)
1. Open [this Colab notebook](https://colab.research.google.com) (or create new)
2. Paste the full code (I can send it - just say 'yes')
3. Click **Run all**
4. Follow the prompts:

Выберите федеральный округ:
1. Центральный → [Белгород, Брянск, Воронеж, Иваново, Калуга, Кострома, Липецк, Красногорск, Ярославль, Тула, Тамбов, Тверь, Владимир, Москва, Орел, Рязань, Смоленск]
2. Северо-Западный → [Петрозаводск, Сывтывкар, Псков, Санкт-петербург, Мурманск, Архангельск, Вологда, Великий новгород, Калининград, Нарьян-мар]
3. Южный → [Астрахань, Волгоград, Черкесск, Ростов-на-дону, Краснодар, Элиста, Ставрополь]
4. Северо-Кавказский → [Черкесск, Нальчик, Махачкала, Владикавказ, Магас, Донецк, Симферополь, Луганск, Майкоп, Грозный, Севастополь]
5. Приволжский → [Оренбург, Пенза, Самара, Екатеринбург, Нижний новгород, Казань, Пермь, Уфа, Йошкар-ола, Саранск, Ижевск, Чебоксары, Ульяновск, Саратов, Киров]
6. Уральский → [Екатеринбург, Ханты-мансийск, Новосибирск, Омск, Салехард, Челябинск]
7. Сибирский → [Томск, Абакан, Красноярск, Улан-удэ, Горно-алтайск, Кызыл, Барнаул, Чита, Иркутск, Кемерово]
8. Дальновосточный → [Петропавловск-камчатский, Якутск, Владивосток, Биробиджан, Анадырь, Благовещенск, Хабаровск, Южно-сахалинск, Магадан]

Номер округа: 2

Города в Северо-Западный:
1. Петрозаводск
2. Сывтывкар
3. Псков
4. Санкт-петербург
5. Мурманск
6. Архангельск
7. Вологда
8. Великий новгород
9. Калининград
10. Нарьян-мар

Номер города:1

 Погода в Петрозаводск:
  Температура: -10.3°C
  Ветер: 3.2 м/с

Запрос сохранён в history.txt

## Files
- `weather.py` - main script (with districts + coordinates)
- `weather_log.txt` - auto-generated history of queries

## Made with
- Curiosity
- Python 3.10+
- Open-Meteo (free weather API)
- All cities are offical regional centres of Russia

>*'I didn't copy - I built it.'*
> - Misha, Vladimir, Russia
