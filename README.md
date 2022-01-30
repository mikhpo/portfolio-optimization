<div class="row" align="center"><img src=".\images\python-logo-generic.svg" width="24%"> <img src=".\images\pandas.svg" width="30%"> <img src=".\images\numpylogo.svg" width="20%"></div></center>

# Инвестиционный анализ

Репозиторий для аналитики, связанной с инвестиционным анализом. На данный момент содержит скрипт на Python в формате Jupyter ноутбука - `portfolio_optimization.ipynb`, в котором реализован метод Шарпа для портфельной оптимизации двумя способами:

1. Симуляцией Монте-Карло.
2. Алгоритмом SLSQP библиотеки SciPy.

Вычисления в ноутбуке периодически обновляются.

Для управления зависимостями в проекте используется Poetry.

## Содержание репозитория

* `notebooks` - директория с ноутбуками.
* `images` - логотипы использованных библиотек.
* `pyproject.toml` - описание пакета для Poetry и основные зависимости.
* `poetry.toml` - конфигурация Poetry.
* `poetry.lock` - подробное описание зависимостей.

## Подготовка перед запуском

Можно использовать виртуальное окружение для запуска скрипта. Для создания виртуального окружения можно использовать стандартную библиотеку venv. Все зависимости зафиксированы в `requirements.txt`. Для установки зависимостей наберите команды:

    python -m venv .venv
    .venv/scripts/activate
    pip install -r requirements.txt
    
Альтернативный и рекомендуемый способ управления зависимостями - через [Poetry](https://python-poetry.org/):

    poetry install
