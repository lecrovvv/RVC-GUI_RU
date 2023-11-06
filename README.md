<div align="center">

<h1>RVC GUI_RU<br><br>
  
Поддерживает только аудио файлы</div>

## GUI

![GUI](https://github.com/Tiger14n/RVC-GUI/raw/main/docs/GUI.JPG)
 <br><br>
Русская локализация для RVC-GUI

<br>

## Подготовка окружения

* Установите Python версии +3.8 если не установлена:

* Выполните данные комманды

Windows с видеокартой Nvidia 
```bash
python -m pip install -U pip setuptools wheel
pip install -U torch torchaudio --index-url https://download.pytorch.org/whl/cu118
pip install -r requirements.txt
```
Другие
```
python -m pip install -U pip setuptools wheel
pip install -U torch torchaudio 
pip install -r requirements.txt
```

Apple silicon Mac
```
pip install --pre torch torchvision torchaudio --extra-index-url https://download.pytorch.org/whl/nightly/cpu

export PYTORCH_ENABLE_MPS_FALLBACK=1
```
<br>

* Установите [hubert_base.pt](https://huggingface.co/lj1995/VoiceConversionWebUI/resolve/main/hubert_base.pt/) и поместите в корневой директории

<br>
 
* Затем запустите данную комманду в коммандной строке:
```bash
python rvcgui.py
```
Или запустите этот файл из корневой директории
```
RVC-GUI.bat
```

# Загрузка моделей
Нажмите кнопку "импорт" чтобы импортировать модель из .zip файла, 
* .zip файл должен содержать файл с расширением".pth". 
* .zip желательно должен содержать ".index" файл.

Или распакуйте модель самостоятельно в папку "Models"
```
models
├───НазваниеМодели1
│   ├───xxxx.pth
│   ├───xxxx.index
│   └───xxxx.npy
└───НазваниеМодели2
    ├───xxxx.pth
    ├───...
    └───...
````
<br>


<br> 

### Как получить модели?.
* Зайдите на discord сервер [ AI Hub](https://discord.gg/aihub)  
* [Модели от сообщества на HuggingFace](https://huggingface.co/QuickWick/Music-AI-Voices/tree/main)

<br>

# Важно!
Что делать если вы нашли ошибку в переводе.
Напишите мне в discord! Не засоряйте пуллами!
Discord: weirdoo.exe
