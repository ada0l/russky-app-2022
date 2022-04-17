# russky-app-2022
Some application to demonstrate DevOps work



* Run tests
    ```bash
    make test
    ```
* Run linters & prettify
    ```bash
    make plint
    ```
* Run server
    ```bash
    make run
    ```

## Cheatsheets

### Start ELK

```bash
sudo sysctl -w vm.max_map_count=262144
```
  
## TODO

* secrets - credentials of blob storage
* docker-compose with:
    * jaeger
    * ELK
    * Grafana