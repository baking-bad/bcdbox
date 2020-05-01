# Baking Bad Box
A customizable local development environment.

## Basic setup: Better Call Dev explorer & dashboard
1. Ensure your local node is exposed at `172.17.0.1:8732`
2. Make sure ports `8080` (web app) and `14000` (api) are not in use
3. Launch BCD
```
make bcd
```
By default BCD is available at https://localhost:8080
4. Stop BCD
```
make bcd-stop
```
5. Delete all data
```
make bcd-clear
```