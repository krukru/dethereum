1. Run `sh install.sh` to install Parity client. Parity is one of the possible ethereum client implementations and is the main one we will be using
2. Run `sh start.sh` to connect to DeThereum network
3. To avoid creating a new account and typing the recovery phrase, you will import an existing account from a recovery phrase. While parity is running run `curl --data '{"method":"parity_newAccountFromPhrase","params":["MY_USERNAME", "MY_USERNAME"],"id":1,"jsonrpc":"2.0"}' -H "Content-Type: application/json" -X POST localhost:8545`
