# Django-Mpesa-Intergration
Django Mpesa Apis
M-Pesa is a mobile phone-based money transfer, financing and microfinancing service, launched in 2007 by Vodafone for Safaricom and Vodacom the largest mobile network operators in Kenya and Tanzania.

M-Pesa allows users to deposit, withdraw, transfer money and pay for goods and services (Lipa na M-Pesa) easily with mobile devices. M-Pesa has spread quickly like wildfire, and by 2010 had become the most successful mobile-phone-based financial service in the world.

With M-Pesa winning the heart and souls of the masses, there was a section of the population who yearned for more. These were the software developers, they wanted an API to access the M-Pesa products. Safaricom responded to them by giving them the M-Pesa G2 API. This was welcomed but only a handful of developers were able to integrate their apps with it. Some did not have the infrastructure nor the technical know-how to do the integrations because of its requirements which included: VPN connection, soap protocol, etc.

Safaricom recently introduced a new M-Pesa API dubbed ‘The Daraja API’ (Daraja in Swahili means bridge) to try and bridge this gap for developers. You can access this API over the public internet a step up from the G2 API which required a VPN connection. The other change was that it communicated over the REST protocol, this was to try and alleviate the pain of the developers whose Apps use REST protocol but had to find a way to accommodate M-Pesa’s SOAP. Daraja API not only had the old services from G2 API(C2B, B2C, and reversal) but also exposed new M-Pesa services(B2B, Transaction status, Account balance, and Lipa na M-Pesa online)
