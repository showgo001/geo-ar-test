# geo-ar-test

https://showgo001.github.io/geo-ar-test/


## for development

`docker-compose up` 後にhttps://0.0.0.0へアクセスするとdocs以下へsslでルーティングされます

スマホのカメラで接続する場合はhostPCと同一ネットワークに置いた上で、
docker-compose.yml内のyourhostdomain.comをhostPCのIPなどにしてください。

PCのカメラを使う場合はssl接続する必要はないので、
docker-composeは編集せずhostpcのIPに8080版ポートでhttp接続してマーカーを表示してください
