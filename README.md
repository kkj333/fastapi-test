# fastapi-test

poetryのテスト用として、fastapiのフレームワークを試してみます。

[参考]('https://fastapi.tiangolo.com/ja/')

``` bash
# set up
poetry init -n
poetry add fastapi
poetry add uvicorn[standard]

# run
poetry run uvicorn main:app --reload
```

[URL]('http://localhost:8000/')

[URL]('http://localhost:8000/docs')
