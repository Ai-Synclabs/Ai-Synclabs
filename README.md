dbsentinel/
├── haproxy_log_to_pg.py          # HAProxy log → PostgreSQL
├── haproxy_client_exporter.py    # Prometheus exporter (:9547)
├── grafana_dashboard.json        # Hazır Grafana dashboard
├── haproxy.cfg                   # Örnek HAProxy konfigürasyonu
│
├── agents/
│   ├── pg/                       # PostgreSQL agent
│   ├── mysql/                    # MySQL / MariaDB agent
│   ├── mongo/                    # MongoDB agent
│   ├── redis/                    # Redis agent
│   ├── elastic/                  # Elasticsearch agent
│   ├── opensearch/               # OpenSearch agent
│   ├── couchbase/                # CouchBase agent
│   ├── datastax/                 # DataStax / Cassandra agent
│   ├── singlestore/              # SingleStore agent
│   ├── yugabyte/                 # YugabyteDB agent
│   ├── rockset/                  # Rockset agent
│   └── vector/
│       ├── pgvector.py           # PostgreSQL + pgvector
│       ├── redis_vector.py       # Redis Vector Search
│       ├── pinecone.py           # Pinecone
│       ├── qdrant.py             # Qdrant
│       ├── chroma.py             # Chroma
│       ├── vespa.py              # Vespa
│       ├── lancedb.py            # LanceDB
│       ├── marqo.py              # Marqo
│       ├── mongo_vector.py       # MongoDB Atlas Vector
│       └── opensearch_vector.py  # OpenSearch kNN
│
└── dashboards/
    ├── haproxy_connections.json
    ├── postgresql_performance.json
    ├── redis_monitoring.json
    └── vector_db_latency.json
