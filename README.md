# Турнирная таблица

## Описание

Есть игровая платформа, обрабатывающая игровые события(результаты игроков в рамках игры). 

Турнир - игровое событие у которого есть время начала и время конца, а так же игры для которой этот 
турнир создан.

У каждого турнира есть турнирная таблица. 

Турнирная таблица - это результаты игроков по отношению друг к другу. Игрок не имеет места в 
турнирной табличке пока не сгенерирует хотя бы одно событие для игры которая привязана к определенному 
турниру. У игроков в турнирной табличке есть место а так же количество набранных очков. После окончания 
турнира результаты в таблице не меняются. 

## Данные
Данные в систему поступают в виде сообщений следующих типов:

 - TournamentStarted(String tournamentId, Set<String> gameIds);
 - TournamentFinished(String tournamentId);
 - PlayerEvent(String playerId, String gameId, Integer points);

## Задача
Написать реализацию турниров и турнирых таблиц(интерфейсы TournamentProcessor, Tournament, Leaderboard).

В проекте вы можете увидеть примерную(по нашему мнению крайне нелепую) реализацию чтоб понять логику 
и поставленную задачу. 

Подумайте чего не хватает этому проекту. Что можно улучшить? Попытайтесь решить задачу наиболее оптимальным 
и изящным способом. 

Сделав задачу - выложите его на GitHub/BitBucket etc и оставьте ссылку на ваше решение в форме. Комментарии(например мысли о том как бы вы идеально реализовали 
данную задачу) можете оставить в секции "комментарии" ниже.

## Комментарии
~~место для ваших комментариев~~ 
