# coinmon
利用命令行，实时产看比特币价格变化：
  确保你的系统上安装了 Node.js 和 Npm，从终端运行以下命令安装 Coinmon。
  
    sudo npm install -g coinmon
  运行coinmon,查看前10大比特币价格:
  
    conimon是从 coinmarketcap.com API 获取所有详细信息。
  还可以使用 -t 标志查看最高的 n 位加密货币，例如 20。
  
    coinmon -t 20
  还可以使用 -c 标志将价格从美元转换为另一种货币。  
  
    coinmon -c inr
 也可以使用加密货币的符号来搜索价格。
 
    coinmon -f btc   
    
Coinmon 支持 AUD、BRL、CAD、CHF、CLP、CNY、CZK、DKK、EUR、GBP、HKD、HUF、IDR、ILS、INR、JPY、KRW、MXN、MYR、NOK、NZD、PHP、PKR、PLN、RUB、SEK、SGD、THB、TRY、TWD、ZAR 这些货币。    
