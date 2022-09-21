## start command
- Build docker-compose
  - `docker-compose build`
- Create React Project
  - React+Typescript: `docker-compose run --rm frontend sh -c 'npx create-react-app frontend --template typescript'`
  - React+Redux+Typescript: `docker-compose run --rm frontend sh -c 'npx create-react-app frontend --template redux-typescript'`
- Start up docker-compose
  `docker-compose up -d`

## Memo
Set host port 3008 in docker-compose.yml in order to avoid port conflict with Vivado/Vitis

