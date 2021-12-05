# AIS Birthday Bot

Birthday bot that reads names & dates from a google sheet & posts birthday messages to a slack channel.

### Local Development

##### Download service account credentials from [Google Cloud Console](https://console.cloud.google.com). 

 - Open Membership-Portal project in Google Cloud
 - Navigate to `IAM & Admin` > `Service Accounts`
 - Open `birthday-bot` service account
 - Open `Keys` tab, select Add Key & click `Create New Key`
 - Create a JSON key and download it

##### Set environment variables

```
export GOOGLE_APPLICATION_CREDENTIALS=/path/to/birthday-bot-credentials.json
export SLACK_CHANNEL_ID=birthday-bot-channel-id
```

##### Build and run

```
npm run build
npm start
```
### Questions

Reach out to [Harsha Srikara](@harshasrikara) for any questions.