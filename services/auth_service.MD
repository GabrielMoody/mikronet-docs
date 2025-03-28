# Authentication Service

## Responsibilites
- Handle all user roles authentication
- Generate JWT token

## API Endpoints

|Method| Endpoint | Description |
|------|----------|-------------|
| POST | /auth/register/user | Create a new account for passenger|
| POST | /auth/register/driver | Create a new account for driver|
| POST | /auth/login | Authenticate a user |
| POST | /auth/reset-password | Request a reset password |
| PUT | /auth/reset-password/{id} | Reset a password via link sent in email|
| PUT | /auth/change-password | Make a new password|

🔗 Repository for [Authentication Servivce](https://github.com/GabrielMoody/mikronet-auth-service)
📜 Refer to [API Documentation](../api-docs/openapi.yaml) for detailed specs.