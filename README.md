
# Paypal Payment Gateway Integration with Spring boot




## Update application.Yml
```bash
server.port=9189
twilio.AccountSID= .......(update your AccountSID)
twilio.AuthToken=..........(update your AuthToken)
twilio.phoneNumber=........(update your phoneNumber)
```
## Dependecies
```bash
<dependency>
			<groupId>com.paypal.sdk</groupId>
			<artifactId>paypal-core</artifactId>
			<version>1.7.2</version>
		</dependency>

		<dependency>
			<groupId>com.paypal.sdk</groupId>
			<artifactId>rest-api-sdk</artifactId>
			<version>1.14.0</version>
		</dependency>
 ```



