// Request
curl -H "content-type: application/json" -X POST --data '{"id":0,"jsonrpc":"2.0","method":"eth_blockNumber","params":[]}' https://eth.blockscout.com/api/eth-rpc
// Response
{
  "jsonrpc": "2.0",
  "result": "0xfa0b0e",
  "id": 0
}
