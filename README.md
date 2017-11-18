Measure Selection (Tools Effect)
 https://forums.getpaint.net/topic/26236-measure-selection-tools-effect/

 Как устанавливать Plugin, описано в файле MeasureSelection.ReadMe.txt, который находится внутри архива zip.

Для того чтобы внутри редактора Paint<span></span>.NET работала горячая коавиша `Alt+c+c`, необходимо сделать следующее.  В файле `C:\Program Files\Paint.NET\Effects\MeasureSelection.dlc` удалить строчки
 ```
 MeasureSelection.SubmenuName=Tools
  =Werkzeuge
 ```
 Вставить знак `&` в `Measure Sele&ction`. В Paint<span></span>.NET должен быть выбран английский язык.