## 责任链模式
### 介绍
使多个对象都有机会处理请求，从而避免了请求的发送者和接受者之间的耦合关系。
将这些对象连成一条链，并沿着这条链传递该请求，直到有对象处理它为止.


JDK
- java.util.logging.Logger#log()
- Apache Commons Chain
- javax.servlet.Filter#doFilter()
