# Как использовать `image_parser.py`

`python image_parser.py -u http://example.com/page/{} -s 1 -e 10 -o broken_images.txt`

`image_parser.py` - Имя Python-файла 

`-u`- ссылка на которой нужно найти битые изображения( фигурные скобки нужны для того что бы код подставлял страницы)

`(-s)` и `(-e)` - начальная и конечная страниццы

`-o broken_images.txt` -  Имя файла в котором сохраятся ссылки на битые изображения
