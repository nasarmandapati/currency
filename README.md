# currency
<!DOCTYPE html>
<html lang="en">

<head>
    <meta charset="UTF-8">
    <meta http-equiv="X-UA-Compatible" content="IE=edge">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Currency Converter</title>
    <link rel="stylesheet" href="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/css/bootstrap.min.css">
    <script src="https://ajax.googleapis.com/ajax/libs/jquery/3.5.1/jquery.min.js"></script>
    <script src="https://cdnjs.cloudflare.com/ajax/libs/popper.js/1.16.0/umd/popper.min.js"></script>
    <script src="https://maxcdn.bootstrapcdn.com/bootstrap/4.5.2/js/bootstrap.min.js"></script>

    <link rel="preconnect" href="https://fonts.gstatic.com">
    <link href="https://fonts.googleapis.com/css2?family=Amiri&family=Lobster&family=Pacifico&display=swap" rel="stylesheet">

    <link rel="stylesheet" href="style.css">
</head>

<body>

    <h1 class="heading text-center display-2">
        Currency Converter
    </h1>
    <hr>
    <div class="container">
        <div class="main">
            <div class="form-group">
                <label for="oamount">
                    Amount to Convert:
                </label>
                <input type="text" class="form-control searchBox" placeholder="0.00" id="oamount">
            </div>
            <div class="row">
                <div class="col-sm-6">
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text">From</span>
                        </div>
                        <select class="form-control from" id="sel1">
                            <option value="">Select One …</option>
                            <option value="USD">USD</option>
                            <option value="AED">AED</option>
                            <option value="ARS">ARS</option>
                            <option value="AUD">AUD</option>
                            <option value="BGN">BGN</option>
                            <option value="BRL">BRL</option>
                            <option value="BSD">BSD</option>
                            <option value="CAD">CAD</option>
                            <option value="CHF">CHF</option>
                            <option value="CLP">CLP</option>
                            <option value="CNY">CNY</option>
                            <option value="COP">COP</option>
                            <option value="CZK">CZK</option>
                            <option value="DKK">DKK</option>
                            <option value="DOP">DOP</option>
                            <option value="EGP">EGP</option>
                            <option value="EUR">EUR</option>
                            <option value="FJD">FJD</option>
                            <option value="GBP">GBP</option>
                            <option value="GTQ">GTQ</option>
                            <option value="HKD">HKD</option>
                            <option value="HRK">HRK</option>
                            <option value="HUF">HUF</option>
                            <option value="IDR">IDR</option>
                            <option value="ILS">ILS</option>
                            <option value="INR">INR</option>
                            <option value="ISK">ISK</option>
                            <option value="JPY">JPY</option>
                            <option value="KRW">KRW</option>
                            <option value="KZT">KZT</option>
                            <option value="MVR">MVR</option>
                            <option value="MXN">MXN</option>
                            <option value="MYR">MYR</option>
                            <option value="NOK">NOK</option>
                            <option value="NZD">NZD</option>
                            <option value="PAB">PAB</option>
                            <option value="PEN">PEN</option>
                            <option value="PHP">PHP</option>
                            <option value="PKR">PKR</option>
                            <option value="PLN">PLN</option>
                            <option value="PYG">PYG</option>
                            <option value="RON">RON</option>
                            <option value="RUB">RUB</option>
                            <option value="SAR">SAR</option>
                            <option value="SEK">SEK</option>
                            <option value="SGD">SGD</option>
                            <option value="THB">THB</option>
                            <option value="TRY">TRY</option>
                            <option value="TWD">TWD</option>
                            <option value="UAH">UAH</option>
                            <option value="UYU">UYU</option>
                            <option value="ZAR">ZAR</option>

                        </select>
                    </div>
                </div>

                <div class="col-sm-6">
                    <div class="input-group mb-3">
                        <div class="input-group-prepend">
                            <span class="input-group-text">To</span>
                        </div>
                        <div class="form-control to">
                            <input type="checkbox" name="currency" value="USD"> USD<br>
                            <input type="checkbox" name="currency" value="AED"> AED<br>
                            <input type="checkbox" name="currency" value="ARS"> ARS<br>
                            <input type="checkbox" name="currency" value="AUD"> AUD<br>
                            <input type="checkbox" name="currency" value="BGN"> BGN<br>
                            <input type="checkbox" name="currency" value="USD"> BRL<br>
                            <input type="checkbox" name="currency" value="AED"> BSD<br>
                            <input type="checkbox" name="currency" value="ARS"> CAD<br>
                            <input type="checkbox" name="currency" value="AUD"> CHF<br>
                            <input type="checkbox" name="currency" value="BGN"> CLP<br>
                            <input type="checkbox" name="currency" value="USD"> CNY<br>
                            <input type="checkbox" name="currency" value="AED"> COP<br>
                            <input type="checkbox" name="currency" value="ARS"> CZK<br>
                            <input type="checkbox" name="currency" value="AUD"> DKK<br>
                            <input type="checkbox" name="currency" value="BGN"> DOP<br>
                            <input type="checkbox" name="currency" value="USD"> EGP<br>
                            <input type="checkbox" name="currency" value="AED"> EUR<br>
                            <input type="checkbox" name="currency" value="ARS"> FJD<br>
                            <input type="checkbox" name="currency" value="AUD"> GBP<br>
                            <input type="checkbox" name="currency" value="BGN"> GTQ<br>
                            <input type="checkbox" name="currency" value="USD"> HKD<br>
                            <input type="checkbox" name="currency" value="AED"> HRK<br>
                            <input type="checkbox" name="currency" value="ARS"> HUF<br>
                            <input type="checkbox" name="currency" value="AUD"> IDR<br>
                            <input type="checkbox" name="currency" value="BGN"> ILS<br>
                            <input type="checkbox" name="currency" value="USD"> INR<br>
                            <input type="checkbox" name="currency" value="AED"> ISK<br>
                            <input type="checkbox" name="currency" value="ARS"> JPY<br>
                            <input type="checkbox" name="currency" value="AUD"> KRW<br>
                            <input type="checkbox" name="currency" value="BGN"> KZT<br>
                            <input type="checkbox" name="currency" value="USD"> MVR<br>
                            <input type="checkbox" name="currency" value="AED"> MXN<br>
                            <input type="checkbox" name="currency" value="ARS"> MYR<br>
                            <input type="checkbox" name="currency" value="AUD"> NOK<br>
                            <input type="checkbox" name="currency" value="BGN"> NZD<br>
                            <input type="checkbox" name="currency" value="USD"> PAB<br>
                            <input type="checkbox" name="currency" value="AED"> PEN<br>
                            <input type="checkbox" name="currency" value="ARS"> PHP<br>
                            <input type="checkbox" name="currency" value="AUD"> PKR<br>
                            <input type="checkbox" name="currency" value="BGN"> PLN<br>
                            <input type="checkbox" name="currency" value="USD"> PYG<br>
                            <input type="checkbox" name="currency" value="AED"> RON<br>
                            <input type="checkbox" name="currency" value="ARS"> RUB<br>
                            <input type="checkbox" name="currency" value="AUD"> SAR<br>
                            <input type="checkbox" name="currency" value="BGN"> SEK<br>
                            <input type="checkbox" name="currency" value="USD"> SGD<br>
                            <input type="checkbox" name="currency" value="AED"> THB<br>
                            <input type="checkbox" name="currency" value="ARS"> TRY<br>
                            <input type="checkbox" name="currency" value="AUD"> TWD<br>
                            <input type="checkbox" name="currency" value="BGN"> UAH<br>
                            <input type="checkbox" name="currency" value="USD"> UYU<br>
                            <input type="checkbox" name="currency" value="AED"> ZAR<br>










                        </div>
                    </div>
                </div>
            </div>

            <div class="text-center">
                <button class="btn btn-primary convert m-2" type="button" onclick="convertCurrency()">
                    Convert
                </button>

                <button class="btn btn-primary m-2" onclick="clearVal()">
                    Reset
                </button>
            </div>

        </div>

        <div id="finalAmount" class="text-center">
            <h2>Converted Amount: <span class="finalValue" style="color:green;"></span></h2>
        </div>
    </div>

    <script>
        function convertCurrency() {
            // Get the amount and currency values
            var amount = parseFloat(document.getElementById('oamount').value);
            var fromCurrency = document.getElementById('sel1').value;
            var toCurrencies = document.querySelectorAll('input[name="currency"]:checked');

            if (isNaN(amount) || amount <= 0) {
                alert('Please enter a valid amount.');
                return;
            }

            if (fromCurrency === '') {
                alert('Please select a currency to convert from.');
                return;
            }

            if (toCurrencies.length === 0) {
                alert('Please select at least one currency to convert to.');
                return;
            }

            var convertedAmounts = [];

            // Perform the conversion for each selected currency
            toCurrencies.forEach(function(currency) {
                var toCurrency = currency.value;
                var conversionRate = getConversionRate(fromCurrency, toCurrency);
                var convertedAmount = amount * conversionRate;

                convertedAmounts.push({
                    currency: toCurrency,
                    amount: convertedAmount.toFixed(2)
                });
            });

            displayConvertedAmounts(convertedAmounts);
        }

        function getConversionRate(fromCurrency, toCurrency) {
            // Implement your conversion rate logic here
            // Return the appropriate conversion rate based on fromCurrency and toCurrency
            // This is a placeholder function, replace it with your actual conversion rate implementation
            return 1;
        }

        function displayConvertedAmounts(convertedAmounts) {
            var finalAmount = document.querySelector('.finalValue');
            finalAmount.innerHTML = '';

            convertedAmounts.forEach(function(convertedAmount) {
                var currency = convertedAmount.currency;
                var amount = convertedAmount.amount;

                finalAmount.innerHTML += amount + ' ' + currency + '<br>';
            });
        }

        function clearVal() {
            document.getElementById('oamount').value = '';
            document.getElementById('sel1').value = '';
            var checkboxes = document.querySelectorAll('input[name="currency"]');
            checkboxes.forEach(function(checkbox) {
                checkbox.checked = false;
            });

            var finalAmount = document.querySelector('.finalValue');
            finalAmount.innerHTML = '';
        }
    </script>
</body>

</html>
