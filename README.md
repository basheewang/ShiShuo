# 《世说新语》有人名索引简体版

## How to build 

    ```bash
    xelatex Main
    makeindex Main
    zhmakeindex Main
    xelatex Main
    xelatex Main
    ```

    如果遇到“? ! LaTeX Error: Counter too large.”的error，只需要ignore即可。
    
    需要使用到 [zhmakeindex](https://github.com/leo-liu/zhmakeindex).
    
    欢迎提出意见或建议。
