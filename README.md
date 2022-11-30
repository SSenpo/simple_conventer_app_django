# simple_conventer_app_django
<div align="center">
    <img width="1287" alt="Снимок экрана 2022-11-30 в 00 55 22" src="https://user-images.githubusercontent.com/90391143/204751158-8c7ec507-d077-4f3a-9ea4-1fee14ad5682.png">
</div>

## Requirements

Everything you need is prescribed in the file ->

```bash
cat pyproject.toml
```

## Installation

Clone this repository:

```bash
git clone https://github.com/SSenpo/simple_conventer_app_django
```
and install poetry:
```bash
pip install poetry
```

Run poetry in repository dir :

```bash
poetry shell
poetry update package
```
<div align="center">
    <img width="1087" alt="Снимок экрана 2022-11-30 в 11 46 57" src="https://user-images.githubusercontent.com/90391143/204751679-a86d18b4-6359-4ea3-97a9-8cd7dc2d5447.png">
</div>

## run server:

```bash
cd conventer_app/
./manage.py migrate
./manage.py createsuperuser

./manage.py runserver #localhost
```
[#localhost](http://127.0.0.1:8000/)
<div align="center">
  <img width="928" alt="Снимок экрана 2022-11-30 в 11 45 57" src="https://user-images.githubusercontent.com/90391143/204751932-3b9f009e-dcac-4c3a-890b-b61949acb83f.png">
</div>

## All detailed information in the [django documentation](https://docs.djangoproject.com/en/4.1/)
