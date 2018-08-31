#Jobs

Jobs should be small.

They should not hold workflow or logic, but rather call service objects holding those workflows.

`ServiceJob` that creates a `Service` and calls it from sidekiq
