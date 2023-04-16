# イメージの指定
FROM python:3.10
# 作業ディレクトリの指定
WORKDIR /usr/src/app
# イメージのビルド時にコマンドを実行
RUN pip install flask==2.1.1
# コンテナの起動時にコマンドを実行（実行されるコマンドは flask run --host=0.0.0.0）
CMD ["flask", "run", "--host=0.0.0.0"]