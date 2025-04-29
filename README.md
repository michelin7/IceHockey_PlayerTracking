# IceHockey_PlayerTracking

## /examples 
- примеры работы системы трекинга (моделей детекции игроков и синих линий, а также смен игроков)
- examples of work Player Tracking System (PlayerDetection model plus BlueLines model and players shifts)

### /examples/players 
- примеры видео смен игроков
- examples of player shifts (result of system work)

## /models 
- модели YOLOv8 для распознавания игроков, их номеров на форме и синих линий
- YOLOv8 models for Player Detection, Player's Number Recognition and Blue Lines Detection

## /trackers 
- настроенный трекер системы
- configured tracker

## /ipynb:excel/Player_tracking.ipynb 
- основной файл для обработки видео. необходимо запускать в Google Colab с подключением Drive, генерирует файл excel со статистикой и нарезки по найденным игрокам. возможен просчет только файла excel
- main file for video analyze. necessary to run code in Google Colab with mounted Drive, generate .xlsx with play by play data and video with players unique ID

## /ipynb:excel/Analytics.xlsx
- анализирует сгенерированный файл excel и преобразует его в конечный вид
- analyze players play by play and transforms player's stats

## /ipynb:excel/Video_processing.ipynb 
- формирует итоговое видео по сменам игроков по уникальному ID из файла Analytics.xlsx
- merge videos by Unique ID from Analytics.xlsx and make video of players shifts
