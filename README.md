# Оркестровка и микросервисы (k8s)

Задача: «Куберизировать» приложение Flask+Redis из предыдущей практики и обновить
 1. Разворачиваем на vm мини-кластер k8s- minikube
 2. (опционально) Подключаемся к кластеру с хостовой машины через приложение Lens
 3. Собираем образы будущих контейнеров и прокидываем их внутрь minikube
 4. Создаем манифесты– описания приложений и сервисов
 5. Разворачиваем deployment/ReplicaSet с application-серверами и БД и сервисы
 6. Активируем балансировщик входящих запросов (служба LoadBalancer)
 7. Проверяем работу сервисов
 8. Обновляем веб сервисы на новую версию (RollingUpdate)
