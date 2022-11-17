# Webpack-project :yellow_heart:
    
    npm install webpack-dev-server -D
    npm install -D webpack-bundle-analyzer
    
## Visualizar dependencias del proyecto  :eyeglasses:
    npx webpack --profile --json > stats.json
    npx webpack-bundle-analyzer stats.json
