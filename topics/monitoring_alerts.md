# Setting Up Monitoring Alerts
Once you have activated your subscribers, you may want to configure monitoring alerts. Monitoring alerts are helpful for protecting against data over usage and bill shock.
There are several options when it comes to setting up monitoring alerts. You can set up alerts that apply to the entire company, to specific groups of subscribers or to individual subscribers. In this topic, we'll look at how to set up an alert for an individual subscriber.
>**Info**: For more information about monitoring alerts, refer to the [User Guide](https://help.iot-x.com/userguide/services/services-user-actions/managing-monitoring-alerts).

This section explains:
* What monitoring alerts are.
* How to set up monitoring alerts for a specific subscriber.
* How to set up monitoring alert recipients.

## What Are Monitoring Alerts?
Monitoring alerts are a notification service provided as part of Pelion. This functionality allows you to:
* Set lower and upper data usage limits at which monitoring alert notifications will be triggered.
* Define data usage limits on a company-wide, group or subscriber-by-subscriber basis.
* Nominate monitoring alert recipients, who will be notified by email when data usage thresholds are reached.

>**Note**: Subscribers are not automatically barred once they reach the defined usage threshold. It is the account holder's responsibility to take appropriate action when a threshold is met.

## Creating Monitoring Alerts for a Specific Subscriber
To create a monitoring alert for a specific subscriber:
1. Navigate to the **Services>Monitoring Alerts** page.
![Monitoring Alerts Page](/images/Blurred Monitoring Alerts Page.png)
2. Click on the **Add Monitoring Alert** button.
3. Refer to the **Add Monitoring Alert** form.
![Add Monitoring Alert Form](/images/Add Monitoring Alert Form.png)
4. Select **Device** from the **Limit Type** drop-down menu.
5. Enter the **Device ID** for the subscriber you want to create an alert for.
6. Specify the lower usage limit at which the monitoring alert will be triggered. This value must be greater than zero.
7. Specify the upper usage limit at which the monitoring alert will be triggered. This value must be greater than the alert’s lower limit.
8. Click on the **Add** button to complete the process.
9. If the monitoring alert was added successfully, a notification like this will appear on screen:
![Success Message](/images/Blurred Monitoring Alert Success Notification.png)

## Setting Up Monitoring Alert Recipients
Once you have created monitoring alerts you need to add the email addresses of the people who you want to receive the alert notifications.

To add a monitoring alert recipient:
1. Navigate to the **Services>Monitoring Alerts** page.
![Monitoring Alerts Page](/images/Blurred Monitoring Alerts Page.png)
2. Refer to the **Monitoring Alert Recipients** panel.
![Monitoring Alert Recipients Panel](/images/Monitoring Alert Recipients Panel.png)
3. Enter the recipient’s email address in the **New Email** text box.
4. Click on the **Add Recipient** button to complete the process.

>**Tip**: As monitoring alert emails may be blocked by spam filters or rejected by the server outright, we recommend that you create a test alert and ensure that emails from Pelion are white-listed.
