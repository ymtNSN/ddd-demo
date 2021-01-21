Domain 模块是核心业务逻辑的集中地，包含有状态的 Entity、领域服务 Domain Service、
以及各种外部依赖的接口类（如 Repository、ACL、中间件等。Domain 模块仅依赖 Types
模块，也是纯 POJO 。