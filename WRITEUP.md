# Write-up

### Analyze, choose, and justify the appropriate resource option for deploying the app.

## VMs
- Usually cost more than App Services to run.
- Could be both scaled up and scaled out (more VM nodes - increases availability), though scaling out adds more operational overhead.

## App Services
- Cheaper to run comparing to VMs.
- Scale out easier comparing to VMs.
- Have more availability.

## Why I've chosen App Service
- Simple CRUD app, so doesn't need much compute resources, therefore App Service looks like a logical choice.
- All the app's use cases could be covered by App Service capabilities.
- App Service is easier to scale, manage and usually faster to deploy.

## App changes that would change my decision.
- App's stack is not yet supported by App Services.
- App requires custom software to run to implement special use-cases.
- App should be deployed in an environment that allows full access and control.