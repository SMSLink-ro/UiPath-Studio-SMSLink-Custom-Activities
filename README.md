# Integration of SMSLink.ro in UiPath using UiPath Studio and SMSLink Custom Activities

Integration of [SMSLink.ro](https://www.smslink.ro) in UiPath using UiPath Studio and SMSLink Custom Activities empowers companies to:

* Send SMS from UiPath using [SMSLink.ro](https://www.smslink.ro) [SMS Gateway API](https://www.smslink.ro/sms-gateway.html);
* Manage [SMSLink.ro](https://www.smslink.ro) account blacklist and contacts from UiPath using [Live Update API](https://www.smslink.ro/sms-marketing-documentatie-live-update.html).

SMSLink.ro allows you to send SMS to all mobile networks in Romania and also to more than 168 countries and more than 1000 mobile operators worldwide. 

## Requirements & Usage

1. Create an account on [SMSLink.ro](https://www.smslink.ro/inregistrare/)
2. Create a SMS Gateway connection at [SMSLink.ro / SMS Gateway / Configuration & Settings](https://www.smslink.ro/sms/gateway/setup.php). Each SMS Gateway connection is a pair of Connection ID and Password. SMS Gateway enables you to send SMS to all mobile networks in Romania and also to more than 168 countries and more than 1000 mobile operators worldwide.
3. Create a Live Update connection at [SMSLink.ro / SMS Marketing / Live Update](https://www.smslink.ro/sms/marketing/liveupdate.php). Each Live Update connection is a pair of Connection ID and Password. Live Update enables you to perform operations on a SMSLink account, operations such as blacklist management and contacts management.
4. Download & install *UiPathTeam.SMSLink.Activities.1.0.0.10.nupkg* from this repository in UiPath Studio.

## Supported Functions for SMSLink SMS Gateway in UiPath Studio

- *SendSMS* - sends an SMS to all mobile networks in Romania and also to more than 168 countries and more than 1000 mobile operators worldwide
- *GetBalance* - retrieve SMSLink account balance

## Supported Functions for SMSLink Live Update in UiPath Studio

- *Blocklist Add* - Adds a Phone Number to the Blacklist in your SMSLink account
- *Blocklist Delete* - Removes a Phone Number from the Blacklist in your SMSLink account     
- *Blocklist Check* - Checks if Phone Number is in the Blacklist in your SMSLink account
- *Add to Group* - Creates a Contact into a Specified Group in your SMSLink account
- *Remove from Group* - Removes a Phone Number from a Specified Group or from All Groups in your 

## System Requirements 

* UiPath Studio  

## Learn More 

Learn more about how to send SMS from an UiPath Robot using SMSLink.ro in this [YouTube video](https://www.youtube.com/watch?v=OpdT07Zn1uY).

## Documentation

The [complete documentation](https://www.smslink.ro/sms-gateway-documentatie-sms-gateway.html) of the SMSLink - SMS Gateway API can be found [here](https://www.smslink.ro/sms-gateway-documentatie-sms-gateway.html), describing all available APIs (HTTP GET / POST, SOAP / WSDL, JSON and more).

The [complete documentation](https://smslink.ro/sms-marketing-documentatie-live-update.html) of the SMSLink - Live Update API can be found [here](https://smslink.ro/sms-marketing-documentatie-live-update.html), describing all available API functions.

## Additional modules and integrations

SMSLink also provides modules for major eCommerce platforms (on-premise & on-demand), integrations using Microsoft Power Automate, Zapier or Integromat and many other useful features. Read more about all available features [here](https://www.smslink.ro/sms-gateway.html). 

## Support

For technical support inquiries contact us at contact@smslink.ro or by using any other available method described [here](https://www.smslink.ro/contact.php).

