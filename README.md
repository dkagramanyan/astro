# AstroNet

Почти готовая (нет) модель нейронной сети для генерации текстовых гороскопов. 
В основе лежит векторное представление слова, конкретно word2vec и метод skip-gram. 

Поставленная цель - решение задачи регрессии. То есть, по входному эмбеддингу слова 
определить эмбеддинг следующего.

Датасет гороскопов с сайта https://horoscopes.rambler.ru

Данные представлены в виде data.csv в формате "date,sign,text". Кодировка текста UTF-8.

73501 запись с 2004 по 2020г

## Пример:

2020-10-21,aries,"Решение проблем и неприятностей будет серьезно буксовать в утренние часы. Важно не злиться, а дождаться правильного момента, нужных обстоятельств, продумать свои действия, чтобы покончить со всеми сложностями одним махом. В ином случае вы наживете себе куда больше трудностей. Вторая половина дня пройдет намного приятнее и легче. Кто-то порадует вас хорошими новостями, а судьбоносные события перезагрузят жизнь. Также звезды готовят вам интересные встречи, которые могут стать началом чего-то очень серьезного."

2020-10-21,gemini,"Очень напряженный день для Близнецов. Настраивайтесь на позитив, меньше нервничайте и тогда вы будете допускать меньше ошибок. Незатуманенный эмоциями мозг поможет оценить обстоятельства объективно, обдумать план и найти верный выход из сложной ситуации, чтобы все закончилось удачно. Вечер лучше отвести на общение с друзьями и членами семьи – приятные эмоции и уютная домашняя атмосфера помогут забыть о непростом утре."

_______________________________________


