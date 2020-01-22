# geo-ar-test

https://showgo001.github.io/geo-ar-test/


## for development

`docker-compose up` 後にhttps://0.0.0.0へアクセスするとdocs以下へsslでルーティングされます

スマホのカメラで接続する場合はhostPCと同一ネットワークに置いた上で、
docker-compose.yml内のyourhostdomain.comをhostPCのIPなどにしてhttps接続してください。

httpsでないと、webRTCを有効化できない場合が多いです。


PCのカメラを使う場合はtls接続する必要はないので、
docker-composeは編集せずhostpcのIPに8080版ポートでhttp接続してマーカーを表示してください
