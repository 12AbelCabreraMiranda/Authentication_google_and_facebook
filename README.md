# Authentication_google_and_facebook
## Authentication Google:

dotnet user-secrets init --project Authentication

dotnet user-secrets set "App:GoogleClientId" "id" --project Authentication

dotnet user-secrets set "App:GoogleClientSecret" "key" --project Authentication


## Authentication Facebook:
dotnet user-secrets set "App:FacebookClientId" "id" --project Authentication

dotnet user-secrets set "App:FacebookSecret" "key" --project Authentication


**Comfiguración realizado:**

*dotnet user-secrets list --project Authentication*
