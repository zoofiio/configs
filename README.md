# configs

bvaults:
````
  Honey-Usdc: 0xE6d15592F337f54E8BD47e56BbB22aF12F0D4083
  Wbera-Weth: 0x94822b9BA715E9e3079ed12489Dc7A016694FC67
  Honey-byusd: 0x6686bDfF3ad20AE45E811c2451DfeE8AA0f338C0


support tokens:
  BERA: '0x6969696969696969696969696969696969696969',
  HONEY: '0xFCBD14DC51f0A4d49d5E53C2E0950e0bC26d0Dce',
  USDC: '0x549943e04f40284185054145c6E4e9568C1D3241',
  BYUSD: '0x688e72142674041f8f6Af4c808a4045cA1D6aC82',
  WETH: '0x2F6F07CDcf3588944Bf4C42aC74ff24bF56e7590',
  iBGT: '0xac03CABA51e17c86c921E1f6CBFBdC91F8BB2E6b',

  additional.json :

    {
      // vault contract address
      "0xE6d15592F337f54E8BD47e56BbB22aF12F0D4083": {
        // epoch start from 1
        "1": {
          "token": "BERA", // token symbol. current support tokens: ['BERA','HONEY','USDC','BYUSD','WETH','iBGT']
          "amount": 400   // token amount
        }
      }
    }
````
