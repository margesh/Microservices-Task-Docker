# Microservices Dockerization

## Services
- User Service (3000)
- Product Service (3001)
- Gateway Service (3003)

## Setup

cd submission
docker compose up --build

## Testing

http://localhost:3000/users
http://localhost:3001/products
http://localhost:3003/api/users

## Troubleshooting

docker compose down
docker compose up --build