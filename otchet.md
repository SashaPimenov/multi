#IO-bound

## Выполнение синхронно в одни поток:
### Время выполнения:
![img.png](screens/img1.png)
### Диспетчер задач
![img.png](screens/img.png)

## Выполнение используя ThreadPoolExecutor:
## max_workers = 5
### Время выполнения:
![img.png](screens/img4.png)
### Диспетчер задач
![img.png](screens/img3.png)

## max_workers = 10
### Время выполнения:
![img.png](screens/img6.png)
### Диспетчер задач
![img.png](screens/img5.png)

## max_workers = 100
### Время выполнения:
![img.png](screens/img8.png)
### Диспетчер задач
![img.png](screens/img7.png)

## При преобразованиях время выполнения уменьшается, а загрузка памяти отличается буквально на пару процентов, процессор(цп) в основном тоже одинаков, но бывают некие скачки и получается заметное отличие

#CPU-bound