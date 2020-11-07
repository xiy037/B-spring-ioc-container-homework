Q:@Component 已经可以支持声明一个 bean 了，为何还要再弄个 @Bean 出来？

A: 
1. 如果class不在spring container里面，可以用@Bean和@Configuration去声明一个bean class.

2. @Bean可以用在method上。
