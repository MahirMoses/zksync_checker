# ZKSync Viewer
Проверка активности кошелька в сети ZKSync.

С помощью программы можно проверить любой EVM-кошелёк и узнать кол-во транзакций, кол-во взаимодействий с приложениями и использование официального моста на ввод. В файле ``resources/contracts.json`` можно добавить контракты других приложений по желанию.

Также просчитываются суммы всех активов (ETH, USDC и USDT показывают реальную стоимость, остальные активы – только баланс самого токена) и затраты на комиссию.
Можно просмотреть указанный кошелёк в Etherscan или в эксплорере ZKSync Era.

## Установка
Требуется **Python 3.9+**! Работа проверена на Python 3.9 / 3.11.5.

1. "Клонировать" репозиторий: ``git clone https://github.com/IAmScRay/zksync_checker/ && cd zksync_checker``
2. Загрузить и установить требуемые зависимости: ``pip install -r requirements.txt``
3. Запустить программу: ``python3 main.py``
