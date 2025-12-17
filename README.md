# LobeChat DB Coolify Template

## Environment Variables Configuration

The following environment variables must be set in the Coolify UI:

### Database Connection Strings

#### DB_URL_LOGTO
```
postgres://<SERVICE_USER_POSTGRES>:<SERVICE_PASSWORD_POSTGRES>@postgres:5432/logto
```

#### DATABASE_URL_LOBECHAT
```
postgres://<SERVICE_USER_POSTGRES>:<SERVICE_PASSWORD_POSTGRES>@postgres:5432/lobechat
```

### Service Endpoints

- **LOGTO_ENDPOINT** - Set as actual HTTPS URL (no trailing slash)
- **LOGTO_ADMIN_ENDPOINT** - Set as actual HTTPS URL (no trailing slash)
- **LOBECHAT_PUBLIC_URL** - Set as actual HTTPS URL (no trailing slash)

### API Keys

- **OPENAI_API_KEY** - Your OpenAI API key

## Important Notes

- All endpoint URLs must use HTTPS
- Do not include trailing slashes on URLs
- Replace `<SERVICE_USER_POSTGRES>` and `<SERVICE_PASSWORD_POSTGRES>` with your actual PostgreSQL credentials