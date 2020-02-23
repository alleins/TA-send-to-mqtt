# Splunk Alert Action that allows you to send messages to MQTT broker

Author: Dmytro Sobolta
Version: 1.0.0

Updates history:
[1.0.0]
- Initial release

Installation:
- Install this TA on your Search Head
- Navigate to the configuration page of this add-on and configure connection to your MQTT broker. Strongly recommend you to use password authentication on your MQTT broker. It is mandatory to use password authentication in this add-on.
- Click Save

Alert action configuration:
- Create new alert or edit an existing one
- Find the "Trigger Action" menu and click to "Add Actions"
- Select "Send to MQTT"
- Specify MQTT Topic you want to send a message
- Write message you want to send to MQTT Topic in the form below. Also you can use Splunk tokens in your message. Full list of available tokens you can find here https://docs.splunk.com/Documentation/Splunk/8.0.2/AdvancedDev/ModAlertsLog#Pass_search_result_values_to_alert_action_tokens

This add-on tested with CloudMQTT(cloudmqtt.com) message broker

What is MQTT you can read here https://en.wikipedia.org/wiki/MQTT
