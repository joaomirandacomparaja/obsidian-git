# Concept

Morgana will act as an api invoking and authentication service to work along Merlin and other services
It will communicate via gRPC so any service must implement gRPC logic in order to make use of Morgana

# Flow

Morgana will have two functionalities:
- Invoking APIs
- Authenticating those invocations

Any application invoking Morgana will first authenticate those requests through some sort of middleware