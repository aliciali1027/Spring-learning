Start a Spring project
====
https://start.spring.io/


# Spring-learning
Learning Spring on Udemy

How to use CSS, JavaScript and Images in Spring MVC Web App
====
https://www.udemy.com/spring-hibernate-tutorial/learn/v4/t/lecture/5608584?start=0

Deploying To Tomcat using WAR files
====
https://www.udemy.com/spring-hibernate-tutorial/learn/v4/t/lecture/5633776?start=0

Spring MVC Form Tags
====
https://docs.spring.io/spring/docs/5.0.2.RELEASE/spring-framework-reference/web.html#mvc-view-jsp-tags

How to use properties file to load country options
====
https://www.udemy.com/spring-hibernate-tutorial/learn/v4/t/lecture/5940154?start=0

Integrate multiple validation string in one annotation
====
https://www.udemy.com/spring-hibernate-tutorial/learn/v4/t/lecture/7407632?start=0

How to read Dates with Hibernate
====
https://www.udemy.com/spring-hibernate-tutorial/learn/v4/t/lecture/7314676?start=0

How to add Search features
====
We'll add a search box at to the screen and the user can enter a name. On the backend, we'll compare this name to the customer's first name or last name.
Overview of Development Process
1. Create the HTML form
2. Add mapping to the controller
3. Add methods in the service layer to delegate to DAO
4. Add method in the DAO to perfom search
https://www.udemy.com/spring-hibernate-tutorial/learn/v4/t/lecture/6525810?start=0

Exception: No bean name available
====
Check if forgot to add @Component annotation to the java class

Spring Annnotations in details
====
https://blog.csdn.net/coslay/article/details/28321165

Spring常用注解介绍【经典总结】
====
https://blog.csdn.net/u010648555/article/details/76299467


How to solve .m2 repository in POM.xml
====
https://www.idownloadblog.com/2015/02/18/restart-finder-mac/
2) Open . files in terminal
https://blog.csdn.net/testcs_dn/article/details/73740835
3) How to killall Finder
https://blog.csdn.net/u012557538/article/details/78402970
4) how to find .m2 in terminal
https://stackoverflow.com/questions/24496131/where-is-my-m2-folder-on-mac-os-x-mavericks
5) Whole process
https://www.jianshu.com/p/ddd70eedf26f

Spring Boot Whitelabel Error Page
====
https://www.javadevjournal.com/spring-boot/spring-boot-whitelabel-error-page/
https://stackoverflow.com/questions/52501089/spring-boot-primitive-rest-controller-returns-whitelabel-error-page

Thymeleaf Introduction
====
https://www.thymeleaf.org/doc/tutorials/3.0/usingthymeleaf.html#what-is-thymeleaf

Thymeleaf Integration
====
Spring MVC part III: ThymeLeaf integration
https://doanduyhai.wordpress.com/2012/04/14/spring-mvc-part-iii-thymeleaf-integration/

SpringBoot跳转页面详解+thymeleaf
====
https://blog.csdn.net/jintingbo/article/details/81633615

Spring Boot中如何干掉if else
====
https://my.oschina.net/u/3990817/blog/3037029

Thymeleaf + Spring: Property or field 'XX' cannot be found on null 
====
https://stackoverflow.com/questions/50799171/el1008e-property-or-field-content-cannot-be-found-on-object-of-type-java-uti
https://stackoverflow.com/questions/54278668/why-is-my-form-not-passing-information-in-spring-boot

java.lang.numberformatexception for input string null - Cause and Solution
====
Read more: https://javarevisited.blogspot.com/2016/08/javalangnumberformatexception-for-input-string-null-java.html#ixzz5sna0joqQ

How do I resolve “java.lang.NumberFormatException” for input string "161"?
====
https://www.quora.com/How-do-I-resolve-%E2%80%9Cjava-lang-NumberFormatException%E2%80%9D-for-input-string-161

Load image with spring boot thymeleaf
====
<div class="ui segment">
<img src="../static/images/Aboutme.JPEG" alt="" class="ui rounded image" th:src="@{images/Aboutme.JPEG}" />
</div>
https://stackoverflow.com/questions/51083414/cant-load-image-with-spring-boot-thymeleaf/51083565#51083565?newreg=d87d59e294554dfb93bc144e15c1e422


java.lang.StackOverflowError: null - toString method
====
I assume the @ToString annotation tells some tool you’re using (Lombok?) to generate a toString method that prints the values of all the fields. Each of the classes refer to the other: Product has a Categorie and Categorie has a list of Product instances. So when the toString implementation prints a Categorie, it calls toString on each Product, which then calls toString on its Categorie, etc. Since Product presumably refers to a Categorie which includes that Product in its products list, the toString calls bounce back and forth until the stack overflows. The solution is to avoid printing either Categorie,products or Product.categorie from the toString method.
https://stackoverflow.com/questions/54653734/lombok-java-lang-stackoverflowerror-null-on-tostring-method
https://stackoverflow.com/questions/23973347/jpa-java-lang-stackoverflowerror-on-adding-tostring-method-in-entity-classes

## Intellij IDEA 中生成JAR包及导出 - include project build
https://blog.csdn.net/qq_34120041/article/details/71713205
https://blog.csdn.net/xuemengrui12/article/details/74984731

### 出错的问题
https://blog.csdn.net/qq_37350706/article/details/84325520

### Deploy a JAVA Web Application in DigitalOcean
https://medium.com/@ldclakmal/deploy-a-java-web-application-in-digitalocean-882226dcdbd5

### How to Connect to your Droplet with OpenSSH
https://www.digitalocean.com/docs/droplets/how-to/connect-with-ssh/openssh/

### idea2018 如何将springboot项目打包成只有一个jar包！
https://blog.csdn.net/qq_39802614/article/details/82710229

Spring Frameworks Explanation
====
Spring框架的基本原理分析
https://blog.csdn.net/kingyxfly/article/details/79826333
Spring面试底层原理的那些问题，你是不是真的懂Spring？
https://blog.csdn.net/javaxuexi123/article/details/80804800

