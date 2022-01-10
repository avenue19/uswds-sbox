# uswds-sbox
A simple NPM demo page using the US Web Design System

## USWDS Links
- Project website: https://designsystem.digital.gov
- Github Repository: https://github.com/uswds/uswds

## Setup
### Restore dependencies
```
npm install
```

### Recompile SASS
```
npx gulp build-sass
```

### Run in Docker
```
docker build -t img-uswds-site .
docker run -it -d -p 8080:80 img-uswds-site
```