# Sample applications that uses KEDA
Source code for examples used in blog posts hosted at [https://www.kedify.io/blog](https://www.kedify.io/blog)

| Direcotry                              | Description                          | Used KEDA scalers                   |
| -------------------------------------- | ------------------------------------ | ----------------------------------- |
| [minute-metrics](./minute-metrics)     | This application can be scaled by metrics coming from an REST endpoint that changes value every few minutes  | Metrics API |
| [stable-diffusion](./stable-diffusion) | This application demonstrates scaling AI workloads that runs on GPU-enabled nodes based on a job queue pattern | RabbitMQ Queue |
