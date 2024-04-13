
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

## screenshots

### payment Creation
![Screenshot (127)](https://github.com/HariPoudel49/Paypal-Payment-Gateway-Integration-with-Spring-Boot/assets/85866119/3379203e-7bc5-4201-a383-1b675e264a10)

### sandbox paypal
![Screenshot (128)](https://github.com/HariPoudel49/Paypal-Payment-Gateway-Integration-with-Spring-Boot/assets/85866119/29e693e8-ad4c-418c-81d0-26ecaf84e1fc)

### success message
![Screenshot (129)](https://github.com/HariPoudel49/Paypal-Payment-Gateway-Integration-with-Spring-Boot/assets/85866119/045c9eb3-c401-429c-bc8d-97e9e5b00dc7)

