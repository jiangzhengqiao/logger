#logger 使用说明

```
    go get github.com/jiangzhengqiao/logger
```

```
    import "github.com/jiangzhengqiao/logger"
    
    func main() {
        logger.SetOutputByName(`/Users/jiangzq/data/spider.log`)
        logger.Info(`INFO`)
        logger.Error(`error`)
        logger.Warning(`Warning`)
    }
```

