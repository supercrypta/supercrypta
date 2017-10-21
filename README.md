<!DOCTYPE html>
<html lang="en">
  <head>
    <!-- Global site tag (gtag.js) - Google Analytics -->
    <script async src="https://www.googletagmanager.com/gtag/js?id=UA-108375007-1"></script>
    <script>
      window.dataLayer = window.dataLayer || [];
      function gtag(){dataLayer.push(arguments);}
      gtag('js', new Date());

      gtag('config', 'UA-108375007-1');
    </script>

    <meta charset="utf-8">
    <meta name="viewport" content="width=device-width, initial-scale=1, shrink-to-fit=no">
    <meta name="description" content="cryptocurrency tracking for mac">
    <meta name="author" content="">
    <link rel="shortcut icon" href="https://supercrypta.github.io/supercrypta/favicon.ico" />

    <title>Super Crypta</title>

    <!-- Bootstrap core CSS -->
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/css/bootstrap.min.css" integrity="sha384-/Y6pD6FV/Vv2HJnA6t+vslU6fwYXjCFtcEpHbNJ0lyAFsXTsjBbfaDjzALeQsN6M" crossorigin="anonymous">

     <link href="web/css/cryptodonate.css" rel="stylesheet"/>
     <link href="web/css/cryptodonate.dark.css" rel="stylesheet"/>

  </head>

  <body>

<div id="google_translate_element"></div><script type="text/javascript">
function googleTranslateElementInit() {
  new google.translate.TranslateElement({pageLanguage: 'en', layout: google.translate.TranslateElement.InlineLayout.SIMPLE}, 'google_translate_element');
}
</script><script type="text/javascript" src="//translate.google.com/translate_a/element.js?cb=googleTranslateElementInit"></script>
        
        
      <div class="jumbotron">
          <div class="col-sm-9 mx-auto">
              <h1>Super Crypta</h1>
              <h5>Cryptocurrency Portfolio for macOS' Notification Center</h5>
            
              <p style="padding-top: 5px">
                    <a class="btn btn-primary" href="https://github.com/supercrypta/supercrypta/releases/download/v0.44/SuperCrypta.zip" role="button">Download 0.44</a>
              </p>
            
              <video style="padding-top: 10px; padding-bottom: 20px" width="304" height="600" autoplay loop>
                    <source src="web/supercrypta.mp4" type="video/mp4">
              </video>
            
              <p id="DonateAndHelpDevelopment">
                if you use it and like 'it, please consider making a small donation:
              </p>
<!-- 
              <div class="row">
                  <div class="col-sm-6 col-md-3">
                    <div class="btc"></div>
                  </div>
                  <div class="col-sm-6 col-md-3">
                    <div class="eth"></div>
                  </div>
                  <div class="col-sm-6 col-md-3">
                    <div class="ltc"></div>
                  </div>
                  <div class="col-sm-6 col-md-3">
                    <div class="xmr"></div>
                  </div>
              </div> -->

           
 
      <div id="content">
            <table>
                <tbody>
                    <tr>
                        
                        <td>
                            <div class="btc">
                            </div>
                        </td>
                        <td>
                            <div class="eth">
                            </div>
                        </td>
                        <td>
                            <div class="ltc">
                            </div>
                        </td>
                        <td>
                            <div class="xmr">
                            </div>
                        </td>
                    </tr>
                    
                   
                </tbody>
            </table>
        </div> 

        <script>
            !function(c){var t=document.createElement("script");t.type="text/javascript",t.async=!0,t.onload=c,t.src="web/cryptodonate.js";var e=document.getElementsByTagName("script")[0];e.parentNode.insertBefore(t,e)}(function(){
                    var btcElems = document.getElementsByClassName('btc');
                    for(var i = 0;i < btcElems.length;i++) {
                        var cd = new Fr.CryptoDonate({
                            baseURL: 'web/',


                            strings: {
                                button: 'Bitcoin',
                                buttonTitle: 'Donate {coinName}',
                                coins: {
                                    bitcoin: 'Bitcoin',
                                    ethereum: 'Ether',
                                    litecoin: 'Litecoin',
                                    monero: 'Monero',
                                },
                                dialogHeader: 'Donate {coinName}',
                                dialogHelper: 'Please use this {coin} address to donate. Thanks!',
                                openInWallet: 'Click here to send this address to your wallet.'
                            },



                            address: '1MYZDEpaE7157njrvq8QBmbrgUMB3SSuhx',
                            buttonLarge: btcElems[i].className.match('large') !== null,

                            buttonClass: btcElems[i].className.match('dark') !== null ? 'dark' : '',
                            dialogClass: btcElems[i].className.match('dark') !== null ? 'dark' : ''
                        });
                        cd.appendTo(btcElems[i]);
                    }

                    var ethElems = document.getElementsByClassName('eth');
                    for(var i = 0;i < ethElems.length;i++) {
                        var cd = new Fr.CryptoDonate({
                            coin: 'ethereum',
                            address: '0x4c77a2A8a570D0066A57a5Cf58bE590e7b9D1A5c',
                            baseURL: 'web/',
                            strings: {
                                button: 'Ethereum',
                                buttonTitle: 'Donate {coinName}',
                                coins: {
                                    bitcoin: 'Bitcoin',
                                    ethereum: 'Ethereum',
                                    litecoin: 'Litecoin',
                                    monero: 'Monero',
                                },
                                dialogHeader: 'Donate {coinName}',
                                dialogHelper: 'Please use this {coin} address to donate. Thanks!',
                                openInWallet: 'Click here to send this address to your wallet.'
                            },
                            buttonLarge: ethElems[i].className.match('large') !== null,

                            buttonClass: ethElems[i].className.match('dark') !== null ? 'dark' : '',
                            dialogClass: ethElems[i].className.match('dark') !== null ? 'dark' : ''
                        });
                        cd.appendTo(ethElems[i]);
                    }

                    var ltcElems = document.getElementsByClassName('ltc');
                    for(var i = 0;i < ethElems.length;i++) {
                        var cd = new Fr.CryptoDonate({
                            coin: 'litecoin',
                            address: 'LQRBruBi9TDHj62U46DU3TNN6fXJrrDyJZ',
                            baseURL: 'web/',
                            strings: {
                                button: 'Litecoin',
                                buttonTitle: 'Donate {coinName}',
                                coins: {
                                    bitcoin: 'Bitcoin',
                                    ethereum: 'Ether',
                                    litecoin: 'Litecoin',
                                    monero: 'Monero',
                                },
                                dialogHeader: 'Donate {coinName}',
                                dialogHelper: 'Please use this {coin} address to donate. Thanks!',
                                openInWallet: 'Click here to send this address to your wallet.'
                            },
                            buttonLarge: ltcElems[i].className.match('large') !== null,

                            buttonClass: ltcElems[i].className.match('dark') !== null ? 'dark' : '',
                            dialogClass: ltcElems[i].className.match('dark') !== null ? 'dark' : ''
                        });
                        cd.appendTo(ltcElems[i]);
                    }

                    var xmrElems = document.getElementsByClassName('xmr');
                    for(var i = 0;i < ethElems.length;i++) {
                        var cd = new Fr.CryptoDonate({
                            coin: 'monero',
                            address: '47cf2ggw9HCXHeNqqRjvu592mpxUci9cNTGfgHRGbkuGUhPMRHacSdE4xgEDf7KNKgACL8Y2pcLPHh3X6DjxjGjXB7Bq7Px',
                            baseURL: 'web/',
                            strings: {
                                button: 'Monero',
                                buttonTitle: 'Donate {coinName}',
                                coins: {
                                    bitcoin: 'Bitcoin',
                                    ethereum: 'Ether',
                                    litecoin: 'Litecoin',
                                    monero: 'Monero',
                                },
                                dialogHeader: 'Donate {coinName}',
                                dialogHelper: 'Please use this {coin} address to donate. Thanks!',
                                openInWallet: 'Click here to send this address to your wallet.'
                            },
                            buttonLarge: xmrElems[i].className.match('large') !== null,

                            buttonClass: xmrElems[i].className.match('dark') !== null ? 'dark' : '',
                            dialogClass: xmrElems[i].className.match('dark') !== null ? 'dark' : ''
                        });
                        cd.appendTo(xmrElems[i]);
                    }
              });
        </script>




        <small style="padding-top: 20px">Cryptocurrency data from <a href="https://coinmarketcap.com" target="_blank">CoinMarketCap</a></small>



            
        </div>



    </div>






    <!-- Bootstrap core JavaScript
    ================================================== -->
    <!-- Placed at the end of the document so the pages load faster -->
      
       <!-- Optional JavaScript -->
    <!-- jQuery first, then Popper.js, then Bootstrap JS -->
    <script src="https://code.jquery.com/jquery-3.2.1.slim.min.js" integrity="sha384-KJ3o2DKtIkvYIK3UENzmM7KCkRr/rE9/Qpg6aAZGJwFDMVNA/GpGFF93hXpG5KkN" crossorigin="anonymous"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.11.0/umd/popper.min.js" integrity="sha384-b/U6ypiBEHpOf/4+1nzFpr53nxSS+GLCkfwBdFNTxtclqqenISfwAzpKaMNFNmj4" crossorigin="anonymous"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.0.0-beta/js/bootstrap.min.js" integrity="sha384-h0AbiXch4ZDo7tp9hKZ4TsHbi047NrKGLO3SEJAg45jXxnGIfYzk4Si90RDIqNm1" crossorigin="anonymous"></script>
      
      

  </body>
</html>


