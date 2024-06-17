# docker-compose
```
docker-compose up -d
docker-compose down

docker-compose start
docker-compose stop
docker-compose restart

docker-compose ps
```
# docker-compose  ModuleNotFoundError: No module named 'XXX'
```
command: bash -c "PYTHONPATH=$$PWD/.. python3 -c 'import sys; print(sys.path)'"
```
注意使用 $$ 来转义docker-compose的环境变量解析



