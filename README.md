# web-ml-grpc-example

<details>
    <summary>
        <strong><em>table of contents</em></strong>
    </summary>
- [backgrounds](#backgrounds)
    - [goals](#goals)
    - [not goals](#not-goals)
- [references](#references)
</details>

## backgrounds
### goals
- enable APIs to communicate via gRPC
  - between web server (written in golang) and ml server (written in Python)
- introduce the idea of `clean architecture` to golang API server
- write Makefile so as to build and run the services

### not goals
- building sophisticated ML models

## references
### gRPC
- [ML Client Server Using gRPC in Python](https://blog.goodaudience.com/ml-client-server-using-grpc-in-python-3cba7693d1f5)

### clean architecture
- [実践クリーンアーキテクチャ](https://nrslib.com/clean-architecture/)
- [POSTD Goでクリーンアーキテクチャを試す](https://postd.cc/golang-clean-archithecture/)
- [5分でわかるクリーンアーキテクチャ](https://www.slideshare.net/kenjitanaka58/5-66290992)
