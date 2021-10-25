# SafeSwapTokenList


# yfdai-farming-coingecko
Coingecko urls
File required to fetch the liquidity and calculate apr for a particular farm
Format: 
{
      "name":"tether", >> NAME OF THE TOKEN
      "tokenProd":"0xdac17f958d2ee523a2206206994597c13d831ec7", >> TOKEN CONTRACT ADDRESS
      "tokenDev":"", >> TESTING TOKEN CONTRACT ADDRESS
      "tokenUrl":"https://api.coingecko.com/api/v3/simple/price?ids=tether&vs_currencies=USD", >> COINGECKO URL TO FETCH PRICE FROM, PLACE THE TOKEN API-ID FOUND ON COINGECKO, REPLACE 'tether' WITH API-ID ON COINGECKO
      "value":null >> FALLBACK VALUE FOR TOKEN PRICE IF AVAILABLE
 },
