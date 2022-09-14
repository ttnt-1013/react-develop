## start command
- docker-compose build
- docker-compose run --rm frontend sh -c 'npx create-react-app frontend --template typescript'
- docker-compose up -d

## Memo
Set host port 3008 in docker-compose.yml in order to avoid port conflict with Vivado/Vitis

