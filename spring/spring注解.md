# spring注解

@Resource

@Autowired

* 共同点

  两者都可以写在字段和setter方法上。两者如果都写在字段上，那么就不需要再写setter方法。

* 不同点

  @Autowire 

    bytype 如果使用byname需要和@Qualifier结合使用

  @Resource

     默认byname 也可以指定bytype 

