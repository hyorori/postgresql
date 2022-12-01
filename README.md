# PostgreSQL環境をつくる

https://zenn.dev/farstep/books/7acd1a7fee7e18/viewer/43e8ed

- yml拝借してプロジェクト直下におき、 `docker-compose up` するだけ。お手軽…
- postgresコンテナの中にはいる `docker container exec -it postgres bash`
- DB一覧を表示 `psql -l`
- yml参考に`psql -U 【ユーザ】 -d 【DB名】`

https://qiita.com/basio/items/6e32d6badd2a002de72c

- `npm install prisma -D`

💬いちからまねしたほうがよさげ

---

# prisma 

公式チュート https://www.prisma.io/docs/getting-started/setup-prisma/start-from-scratch/relational-databases-typescript-postgres

https://qiita.com/dkawabata/items/cafa3dc53921db520360