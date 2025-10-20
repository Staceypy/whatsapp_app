1. Updating the whatsmeow library to the latest version
    cd whatsapp-bridge && go get -u go.mau.fi/whatsmeow
2. Clean up dependencies
    cd whatsapp-bridge && go mod tidy
3. Run the app (default port 8082)
    go run main.go
4. Run the app with custom port
    PORT=8080 go run main.go
5. Run the app in NO_HISTORY mode (only stores messages sent via API)
    NO_HISTORY=1 go run main.go
6. Run the app with both custom settings
    PORT=8080 NO_HISTORY=1 go run main.go