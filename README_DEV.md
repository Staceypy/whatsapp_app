1. updating the whatsmeow library to the latest version
    cd whatsapp-bridge && go get -u go.mau.fi/whatsmeow
2. clean up dependencies
    cd whatsapp-bridge && go mod tidy
3. run the app 
    cd whatsapp-bridge && go run main.go
    