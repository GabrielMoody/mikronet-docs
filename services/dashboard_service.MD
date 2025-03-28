# Dashboard Service

## Responsibilites
- Provide data for monitoring purposes on dashboard
- Handle account management such as blocking and deleting account

## API Endpoints

|Method| Endpoint | Description |
|------|----------|-------------|
| GET | /dashboard/users | Get all passenger accounts|
| GET | /dashboard/drivers | Get all driver accounts|
| GET | /dashboard/reviews | Get all reviews|
| GET | /dashboard/users/{id} | Get passenger account by id|
| GET | /dashboard/drivers/{id} | Get driver account by id|
| GET | /dashboard/reviews/{id} | Get reviews by id|
| GET | /dashboard/block | Get all blocked accounts|
| POST | /dashboard/drivers/verified/:id | verify new driver account|
| POST | /dashboard/block/{id} | Blocking an account |
| PUT | /dashboard/block/{id} | Unblocking an account|
| DELETE | /dashboard/users/{id} | Delete a passenger account|
| DELETE | /dashboard/drivers/{id} | Delete a driver account|

🔗 Repository for [Dashboard Service](https://github.com/GabrielMoody/mikronet-dashboard-service)

📜 Refer to [API Documentation](../api-docs/openapi.yaml) for detailed specs.