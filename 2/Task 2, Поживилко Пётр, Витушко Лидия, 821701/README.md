# АЛГОРИТМЫ СИНХРОНИЗАЦИИ ПРОЦЕССОВ

## Реализация "обедающих философов"

Содержание репозитория:

В качестве вилок используется int переменная, равная 5. Для доступа к вилкам используется мьютекс. Когда философ идет есть, мьютекс блокируется и не освобождается, пока прошлые обедающие философы не вернут вилки (стоит в очереди первым).