# Roop
    

- brew install python@3.10
- python -m ensurepip
- cd roo
- python3 -m venv venv 
- source venv/bin/activate 
- pip install -r requirements.txt
- python run.py -s 'полный путь к фото' -t 'полный путь к изменяемому файлу' -o 'путь куда сохранить'
- `https://github.com/s0md3v/roop?tab=readme-ov-file`

# Faceswap

- cd faceswap
- python3 -m venv faceswapenv
- source faceswapenv/bin/activate
- python -m pip install --upgrade pip
- - For Nvidia GPU users: pip install -r ./requirements/requirements_nvidia.txt
- - For CPU users: pip install -r ./requirements/requirements_cpu.txt
-  python faceswap.py gui
- `https://github.com/deepfakes/faceswap`
- usege `https://github.com/deepfakes/faceswap/blob/master/USAGE.md`