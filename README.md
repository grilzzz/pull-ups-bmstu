Проект про определению правильности подтягиваний

файл `make_data.ipynb` для каждого видео берет его кадры, определяет положение ног(согнуты или прямые, скрещенны или не скрещенны) и в зависимости от этого разбивает картинки по папкам.
используется: mediapipe, opencv, pathlib

файл `ml.ipynb` обучает модель, которая по фотке определяет правильность подтягивания
используется: mediapipe, pandas, sklearn