# equipment-linkage-impl

## 一、Java分层领域模型规约
> 1.0 Ao(ApplicationObject):应用对象，在Web层与Service层之间抽象的复用对象模型， 极为贴近展示层，复用度不高。
> 1.1 Do(Data Object):此对象与数据库表结构一一对应，通过 DAO 层向上传输数据源对象。
> 1.2 Dto(Data Transfer Object):数据传输对象，Service 或 Controller 向外传输的对象。
> 1.3 Bo(Business Object):业务对象，由 Service 层输出的封装业务逻辑的对象。
> 1.5 Vo(View Object):显示层对象，通常是 Web 向模板渲染引擎层传输的对象。
