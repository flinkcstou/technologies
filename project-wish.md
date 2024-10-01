Изучить как это работает

- @ConditionalOnProperty(value = "push-sender.firebase.enabled", havingValue = "true")
- @ConditionalOnBean(FirebaseOptions.class)
- что если внутри бина инициализирую класс и внутри класса использую autowired будет ли работать 