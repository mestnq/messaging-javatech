# Задание:
Переделайте пример приложения из Spring AMQP tutorial, так чтобы оно позволяло обмениваться сообщениями:

При вводе текста и нажатии на enter отправлять сообщение в брокер
При поступлении сообщения из брокера отображать его на экране
Любое отправленное сообщение должно рассылаться на все запущенные копии приложения
Приложение должно взаимодействовать с брокером сообщений, например RabbitMQ

Подсказки:

AMQP запрещает рассылать сообщение из одной очереди больше чем одному клиенту
Для каждого клиента вам понадобится эксклюзивная автоудаляемая очередь с уникальным названием
Для того чтобы сообщение рассылалось во все очереди вам понадобится FanoutExchange
Чтобы изменить тип exchange, его нужно удалить и создать заново
Выложите получившийся проект на github и вставьте в поле ссылку на него.
