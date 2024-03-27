<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Price Landing Page</title>
    <style>
        body {
            font-family: Arial, sans-serif;
            margin: 0;
            padding: 0;
            background-color: #f4f4f4;
        }
        .container {
            max-width: 1000px;
            margin: 50px auto;
            background-color: #e0dede;
            padding: 20px;
            border-radius: 10px;
            box-shadow: 0 0 10px rgba(0, 0, 0, 0.1);
        }
        h1 {
            text-align: center;
        }
        .pricing-table {
            display: flex;
            justify-content: center;
        }
        .plan {
            margin: 10px 10px;
            padding: 20px;
            background-color: #f9f9f9;
            border-radius: 10px;
            box-shadow: 0 0 5px rgba(0, 0, 0, 0.1);
            text-align: center;
            flex: 1;
        }
        .plan h2 {
            margin-top: 0;
        }
        .plan p {
            color: #666;
        }
        .plan .price {
            font-size: 28px;
            font-weight: bold;
            color: #333;
        }
        .plan .features {
            margin-top: 20px;
        }
        .plan .features li {
            margin-bottom: 10px;
        }
        button {
            background-color: #007bff; 
            color: #fff;
            padding: 10px 20px; 
            border: none; 
            border-radius: 5px; 
            cursor: pointer;
            transition: background-color 0.3s; 
        }
        button:hover {
            background-color: #adb2b8; 
        }
        
    </style>
</head>
<body>
    <div class="container">
        <h1>Choose a Plan</h1>
        <div class="pricing-table">
        <div class="plan">
                <div class=""></div>
                <h2>Basic</h2>
                <p class="price">$10/month</p>
                <ul class="features">
                    <li>Email support</li>
                    <li>1 Domain</li>
                    <li>1-day data retention </li>
                    <li>Multi region</li>
                    <li>Single sign on</li>
                    <li>Dedicated IPs</li>
                </ul>
                <button type="button">Buy Now</button>
            </div>
            <div class="plan">
                <h2>Standard</h2>
                <p class="price">$20/month</p>
                <ul class="features">
                    <li>Slack support</li>
                    <li>Unlimited Domains</li>
                    <li>3-Day data retention</li>
                    <li>Multi-Region</li>
                    <li>Single sign-on</li>
                    <li>Dedicated IP with Add on</li>
                </ul>
                <button type="button">Buy Now</button>
            </div>
            <div class="plan">
                <h2>Premium</h2>
                <p class="price">$30/month</p>
                <ul class="features">
                    <ul class="motu"></ul>
                    <li>Priority Support</li>
                    <li>Unlimited Domains</li>
                    <li>Flexible data retention</li>
                    <li>Multi-Region</li>
                    <li>Single sign-on</li>
                    <li>Dedicated IPs included</li>
                </ul>
                <button type="button">Buy Now</button>
            </div>
        </div>
    </div>
</body>
</html>
