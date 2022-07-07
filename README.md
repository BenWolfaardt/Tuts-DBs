# [EdgeDB](https://www.edgedb.com/)
The post-SQL era has arrived!

EdgeDB is an open-source database designed as a spiritual successor to SQL and the relational paradigm. It aims to solve some hard design problems that make existing databases unnecessarily onerous to use.

Powered by the Postgres query engine under the hood, EdgeDB thinks about schema the same way you do: as **objects** with **properties** connected by **links**. It's like a relational database with an object-oriented data model, or a graph database with strict schema. We call it a **graph-relational database**.

## Resources

### Getting Started
* [Quickstart Guide](https://www.edgedb.com/docs/guides/quickstart)
* [Book](https://www.edgedb.com/easy-edgedb) - comprehensive walkthrough of EdgeDB

### Other
* [GitHub](https://github.com/edgedb/edgedb)
* [Python Driver](https://www.edgedb.com/docs/clients/00_python/index):
  * [GitHub](https://github.com/edgedb/edgedb-python)
  * [AsyncIO API](https://www.edgedb.com/docs/clients/00_python/api/asyncio_client#edgedb-python-asyncio-api-reference)
  * [Datatypes](https://www.edgedb.com/docs/clients/00_python/api/types#edgedb-python-datatypes)
* [Examples](https://github.com/edgedb/edgedb-examples):
  * [FastAPI](https://github.com/edgedb/edgedb-examples/tree/main/fastapi-crud) - [Tutorial](https://www.edgedb.com/docs/guides/tutorials/rest_apis_with_fastapi)
  * [Flask](https://github.com/edgedb/edgedb-examples/tree/main/flask-crud) - [Tutorial](https://www.edgedb.com/docs/guides/tutorials/rest_apis_with_flask)
  * [Strawberry **GraphQL**](https://github.com/edgedb/edgedb-examples/tree/main/strawberry-gql) - [Tutorial](https://www.edgedb.com/docs/guides/tutorials/graphql_apis_with_strawberry)
* Deployment:
  * [Docker](https://www.edgedb.com/docs/guides/deployment/docker)
  * [Bare Metal](https://www.edgedb.com/docs/guides/deployment/bare_metal)