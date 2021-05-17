 python-web-scraping-examples

## BandLeader

Пример кода, найденный в `bandleader.py`, сопровождает [это] (https://realpython.com/blog/python/modern-web-automation-with-python-and-selenium/) сообщение на [realpython.com] ( https://realpython.com). Он знакомит читателя с использованием Python для управления автономными веб-браузерами. В частности, `bandleader.py` позволяет воспроизводить музыку из [bandcamp] (https://bandcamp.com) через оболочку Python!

Чтобы поиграть с `bandleader.py`, см. [Руководство] (https://realpython.com/blog/python/modern-web-automation-with-python-and-selenium/) для настройки, затем запустите что-то вроде:


`` питон

>>> из бандлидера импортировать BandLeader
>>> bl = BandLeader ('myhistory.csv')
>>> bl.play () # должен начать воспроизведение трека

>>> bl.play (3) # проигрывает третий трек в листинге

>>> bl.play_next () # продвигает трек вперед
 
>>> bl.more_tracks () # увидеть больше музыки для игры

>>> bl.browser.quit () # закрываем экземпляр webdriver

`` ''