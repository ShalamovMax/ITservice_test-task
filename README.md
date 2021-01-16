
# ITservice_test_task the shortest way

Demo REST which find the shortest way beetwen two cities

To start the service you need to copy the content of this repository and run `docker-compose up` inside this folder.

## Example

If you want to get the distance from city 0 to city 42 you can use the following command:
```bash
curl -i -H 'x-api-key: 123321' "http://localhost:5000/distance?city_start=0&city_finish=42"
```

## Usage

To run this project locally you need only [`Docker`](https://www.docker.com/):

1. Clone [this repo](https://github.com/ShalamovMax/ITservice_test-task) (or download)
2. Run `docker-compose up` in the root of the project
3. Wait for the installation to finish⏳
