# Всем привет, Меня зовут Сергей

## Мои проекты:
  ### - [Отправка нотификаций в Telegrma Bot](https://github.com/CorporationX/notification_service/tree/werewolf-master/src/main/java/faang/school/notificationservice/service/notification/telegram)
  ### - Сервис нотификаций: [user service](https://github.com/CorporationX/user_service/blob/werewolf-master/src/main/java/school/faang/user_service/publisher/AbstractEventPublisher.java) публикует событие в [Redis](https://github.com/CorporationX/user_service/blob/werewolf-master/src/main/java/school/faang/user_service/publisher/SkillOfferedEventPublisher.java), notification service потребляет все эти [события из соответствующих очередей](https://github.com/CorporationX/notification_service/blob/werewolf-master/src/main/java/faang/school/notificationservice/listener/SkillOfferListener.java), [обрабатывает](https://github.com/CorporationX/notification_service/blob/werewolf-master/src/main/java/faang/school/notificationservice/listener/AbstractEventListener.java), собирает все необходимые данные для построения тела [нотификации](https://github.com/CorporationX/notification_service/blob/werewolf-master/src/main/java/faang/school/notificationservice/message/SkillOfferMessageBuilder.java), а также контакты получателя, а затем отправляет нотификацию через предпочитаемый получателем способ доставки: Google SMTP (email), Vonage (sms), Telegram.
  ### - Сервиc достижений: все сервисы публикуют разнообразные события о пользователях, которые могут внести вклад в получение ими тех или иных достижений в соответствующие топики в Redis. achievement_service подписывается на те топики, которые содержат события, приводящие к достижениям. [Алгорим присвоения достижения](https://github.com/CorporationX/achievement_service/blob/werewolf-master/src/main/java/faang/school/achievement/handler/AbstractHandler.java).
  ### - Добавление файлов в хранилище Minio (используется Amazon S3 для манипулирования файлами): [link1](https://github.com/CorporationX/project_service/pull/217/files#diff-d9c6e60b7f8197d4324c636c02acb27acb0b1974ce09b99b5f0691c8c281ffff), [link2](https://github.com/CorporationX/project_service/pull/217/files#diff-9b2f9b7a3c5aaac5c54ce29fc3a332cc1285c368bd977e504531c0809cc7de5b)
  ### - [Формирование платежного счета](https://github.com/CorporationX/account_service/blob/werewolf-master/src/main/java/faang/school/accountservice/service/AccountService.java)    
<!---
### Visitor count
<img src="https://profile-counter.glitch.me/czar777/count.svg" />


<div>
    <img src="https://cultofthepartyparrot.com/parrots/hd/githubparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/flags/hd/indiaparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/asyncparrot.gif" width="36" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/exceptionallyfastparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/60fpsparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/jumpingparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/opensourceparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/dealwithitnowparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/hypnoparrotlight.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/databaseparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/fixparrot.gif" width="36" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/laptop_parrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/spinningparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/levitationparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/meldparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/slomoparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/moonwalkingparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/stableparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/scienceparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/pirateparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/footballparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/illuminatiparrot.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/hypnoparrotdark.gif" width="30" height="30"/>
    <img src="https://cultofthepartyparrot.com/parrots/hd/mustacheparrot.gif" width="30" height="30"/>
</div>
-->
