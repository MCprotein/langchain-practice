Jupyter notebook에서 uv 사용 방법

로컬 터미널

1. `$ uv init`
2. `$ uv add --dev ipykernel`
3. `$ uv run ipython kernel install --user --name=myproj`
4. Jupyter notebook 화면에서 커널 선택
5. `$ uv run --with jupyter jupyter lab`

Jupyter notebook cell에서는 !uv로 명령어 사용
