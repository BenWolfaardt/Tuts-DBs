# [EdgeDB](https://www.edgedb.com/)
The post-SQL era has arrived!

EdgeDB is an open-source database designed as a spiritual successor to SQL and the relational paradigm. It aims to solve some hard design problems that make existing databases unnecessarily onerous to use.

Powered by the Postgres query engine under the hood, EdgeDB thinks about schema the same way you do: as **objects** with **properties** connected by **links**. It's like a relational database with an object-oriented data model, or a graph database with strict schema. We call it a **graph-relational database**.

## [CLI Commands](https://www.edgedb.com/docs/cli/index) to remember
The docs are super well written and what I used to fix the bugs that I was struggling with for the whole day... 

> **Read the docs!**

The Instance name in this EdgeDB project is: **`EdgeDB_Quickstart`**

### [edgedb project](https://www.edgedb.com/docs/cli/edgedb_project/index)
EdgeDB provides a way to quickly setup a project. This way the project directory gets associated with a specific EdgeDB instance and thus makes it the default instance to connect to. This is done by creating an `edgedb.toml` file in the project directory.

* `edgedb project init`  
  [Setup a new project](https://www.edgedb.com/docs/cli/edgedb_project/edgedb_project_init#ref-cli-edgedb-project-init)
* `edgedb project info`  
  [Display various metadata about the project](https://www.edgedb.com/docs/cli/edgedb_project/edgedb_project_info#ref-cli-edgedb-project-info)
* `edgedb project unlink​`  
  [Remove association with and optionally destroy the linked EdgeDB instance](https://www.edgedb.com/docs/cli/edgedb_project/edgedb_project_unlink#ref-cli-edgedb-project-unlink)

### [edgedb instance​](https://www.edgedb.com/docs/cli/edgedb_instance/index)
The `edgedb instance` group of commands contains all sorts of tools for managing EdgeDB instances.

* `edgedb instance start <name>`  
  [Start an EdgeDB instance](https://www.edgedb.com/docs/cli/edgedb_instance/edgedb_instance_start#ref-cli-edgedb-instance-start)
* `edgedb instance list​ --extended`  
  [Show all EdgeDB instances](https://www.edgedb.com/docs/cli/edgedb_instance/edgedb_instance_list#ref-cli-edgedb-instance-list)
* `edgedb instance destroy <name> --force`  
  [Remove an EdgeDB instance](https://www.edgedb.com/docs/cli/edgedb_instance/edgedb_instance_destroy#ref-cli-edgedb-instance-destroy)

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
