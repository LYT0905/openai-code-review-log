代码评审：

根据提供的git diff记录，删除了多个包的package-info.java文件。这些包包括：

1. big-market-domain/src/main/java/com/big/market/infrastructure/domain/xxx/adapter/
2. big-market-domain/src/main/java/com/big/market/infrastructure/domain/xxx/model/aggregate/
3. big-market-domain/src/main/java/com/big/market/infrastructure/domain/xxx/model/entity/
4. big-market-domain/src/main/java/com/big/market/infrastructure/domain/xxx/model/valobj/
5. big-market-domain/src/main/java/com/big/market/infrastructure/domain/xxx/repository/
6. big-market-domain/src/main/java/com/big/market/infrastructure/domain/xxx/service/
7. big-market-infrastructure/src/main/java/com/big/market/infrastructure/infrastructure/gateway/adapter/
8. big-market-infrastructure/src/main/java/com/big/market/infrastructure/infrastructure/gateway/api/
9. big-market-infrastructure/src/main/java/com/big/market/infrastructure/infrastructure/gateway/dto/
10. big-market-trigger/src/main/java/com/big/market/infrastructure/trigger/listener/

这些包的删除意味着它们不再被项目使用，可能是由于重构、功能调整或其他原因导致的。在删除这些包之前，请确保已经进行了充分的代码审查和测试，以确保不会引入新的问题或导致现有功能的缺失。同时，也要确保项目中的其他部分没有对这些包的依赖，否则可能会导致编译错误或其他运行时问题。