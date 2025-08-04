# Ecommerce Event Bus

Manages event publishing and subscribing using Kafka or RabbitMQ.

## Setup
1. Install Kafka or RabbitMQ.
2. Configure event topics based on `config/events.yaml`.
3. Run the event bus (configure as needed).

## Events
- `AddressUpdated`: Triggered by User Service.
- `OrderPlaced`: Triggered by Order Service.
- `ProductAddedToCart`: Triggered by Cart Service.
- `PaymentCompleted`: Triggered by Payment Service.

## Dependencies
- Kafka or RabbitMQ
