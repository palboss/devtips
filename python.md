# python javascript web 时间和时区最好处理方法是用UTC时间
javascript
```javascript
let d = new Date();
let UTCTime = Date.now() + d.getTimezoneOffset()*minute;
```
python
``` python
timeline=datetime.utcnow()
```
# ujson 提示 ValueError: Expected object or value
```
data = ujson.loads(tabdata)

##先用 标准库json定位错误：

data = json.loads(tabdata)
```
# Sanic 蓝图注册时会递归地遍历当前序列
注意路径的引用顺序，子包不要引用父包，在父包中引用子包。

# Sanic 21版本移除 sanic-testing
```
pip install sanic-testing 
```