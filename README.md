# gRPC Web Sample
## gRPC-Web
サーバ側をGoとクライアント側をJavaScript(Svelte)でgRPC通信を試すためのサンプルです。

一般的にgRPCはマイクロサービス間で通信を行う際に使われ、クライアントをブラウザにしたい場合はgRPC-Webを利用する。
ブラウザの制限によりネイティブのgRPCとは違う実装。
https://github.com/grpc/grpc-web
https://github.com/grpc/grpc-web/tree/master/net/grpc/gateway/examples/helloworld
https://grpc.io/