# 100Day-ML-Marathon

## 讀取 ipynb 檔   

啟動 jupyterlab 

```sh
docker run --rm -p 8888:8888 -p 4040:4040 -e JUPYTER_ENABLE_LAB=yes -v ~/git/100Day-ML-Marathon:/home/jovyan/work jupyter/all-spark-notebook
```

> 上面是假設檔案放置在 ~/git/100Day-ML-Marathon 裡

依照是示開啟  (每次的 token 會不同)

http://127.0.0.1:8888/?token=a36cd9f80bb64a8bbbc249dfcf791b8132dea39028bb6
