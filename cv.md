#Mirmanov Serik Almaspayevich
___
![My best photo](Serik1.jpg)
____
__ADDRESS__
 Kazakhstan, Aktobe city
__PHONE__
+77011283329
____
__EMAIL__
mirseka@mail.ru
___
__ABOUT ME__
I'm newcomer at programming. I have started my path from Python and realized that it is realy my field. I was born for programming. I know that it will be really hard way, but I believe myself.
>___Progress is never linear___
___
__THE SAMPLE OF CODE__
```Python
from deepface import DeepFace
import json
def face_verify(img_1, img_2):
    try:
        result_dict = DeepFace.verify(img1_path=img_1, img2_path=img_2)

        with open ('result.json', 'w') as file:
             json.dump(result_dict, file, indent=4, ensure_ascii=False)
                 return  result_dict

        if result_dict.get('verified'):
            return 'Проверка пройдена! Пропустить'
        return 'Нарушитель! Задержать'

    except Exception as _ex:
        return _ex
def start():
    print(face_verify(img_1='Jolie.jpg', img_2='fara4.jpg'))
if __name__ == '__main__':
    start()
```
__EDUCATION__
_Zhangir Khan University_, Uralsk, 2019-2021
Master of petroleum engineering
_Zhubanov University_, Aktobe, 2010-2012
Bachelor of Jurisprudence
_National Security Military institute_, Almaty, 2004-2008
Border control specialist
___
__COURSES__
certificate |  date
:-----------|:-------:
Nebosh IGC | 2018
Microsoft Power BI|2022
___
__LANGUAGES__
KAZAKH - Native
RUSIIAN - Advanced
ENGLISH - Intermediate
___
__COMPUTER SKILS__
1. Python
2. MS Office
3. Power BI
___
[My Power BI project link](https://app.powerbi.com/view?r=eyJrIjoiNTI1MTZkMzItMWRhOS00MjFjLTk4MmEtZDU3MTgwMjI1NmMzIiwidCI6IjZlZWVhZjNlLTY3MTItNDhhNC05NzY3LTNmY2E1NGUxMTc1YyIsImMiOjl9)
