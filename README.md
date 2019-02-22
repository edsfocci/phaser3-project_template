# Phaser 3 Project Template with webpack 4
Based on https://github.com/photonstorm/phaser3-project-template

Includes additions to deploy your project to Heroku.

### Requirements / Recommendations
* Node.js
  * &gt;=6.11.5 required for webpack 4 https://github.com/webpack/webpack/blob/v4.0.0/package.json#L71
  * &gt;=8.9.4 recommended for webpack 4 https://twitter.com/wSokra/status/967852475918274561

### webpack 4 Configuration
Uses development defaults:
```javascript
{
  entry: './src/index.js',
  output: // Handled by webpack-dev-server
}
```

Uses production defaults:
```javascript
{
  entry: './src/index.js',
  output: {
    filename: 'main.js',
    path: path.resolve(__dirname, 'dist')
  }
}
```
