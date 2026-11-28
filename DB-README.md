# 통합 검색 DB (db 브랜치)
jhlab.blog 자료(판정례·행정해석·판례·헌재결정례)를 합친 SQLite 를 gzip 후 45MB 조각으로 나눈 것입니다. 자동 갱신됩니다.
복원: `cat labor-all.db.gz.part-* | gunzip > labor-all.db`
기준 시각: labor-all.meta.json 의 generated_at
