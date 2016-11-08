# Setting up a campaign

## Introduction to text message technology

There are countless ways you can send text messages to your community. We are going to focus on two tools that have worked well for us because they are inexpensive, have good customer support, and allow people without programming knowledge to use them. 

These two tools are Twilio and TextIt. Together, they allow you to send text messages at the push of a button. You can think of them like a car: Twilio works as the engine, powering your messages without being seen once you set it up. TextIt is the dashboard that you use to steer and adjust your settings.

Follow along step by step here to set them up for yourself. Note: these instructions are accurate as of October 2016.

## Introduction to Twilio

As your first step, you’ll need to set up a Twilio account. You won’t need to interact with this account much.

- Go to Twilio.com
- Click ‘Sign up’ or ‘Get a free API key’
- Fill out the information of the person who will be administering this account.
- You don’t need to fill out the second half of the form, but you can use the following settings if you’d like to:

![Product: sms. Building: appointment reminders. Language: not a developer.](/img/twilio_signup.png)

- Next, you’ll be asked for a phone number to verify the account. Don’t worry, this isn’t the number you’ll be sending texts from. Use your cell phone.
- Once you’ve verified your account, you’ll be taken to the Console Dashboard. Here you’ll find your Account SID and Auth Token. Take note of these, you’ll need them for TextIt.

![screenshot of console dashboard](/img/twilio_tokens.png)

- As your last step with Twilio, you’ll need to add money to your account. You’re currently in a free trial mode, but to send texts, you’ll need to add funds. Click on the “Upgrade” link. You can start with just $20.
- If your organization is a 501(c)3 non-profit or certified B-Corp, you may be eligible for free or discounted credits through [Twilio.org](https://www.twilio.org/). Apply through their website after you have followed the steps above to create your account! 

You’re done setting up Twilio. Now it’s time to set up your TextIt account.

## Introduction to TextIt

The tool we'll be using to set up our text message campaign is called TextIt. TextIt is build by a company called [Nyaruka](http://nyaruka.com/), based in Kigali, Rwanda.

TextIt allows you to visually build interactive text message campaigns. You don't need to be a programmer start sending texts. Anyone with a bit of training can set up and administer a campaign. So let’s get started!

- Go to textit.in
- Enter your email address in the “Try it for Free” field. 
- Create an account with your administrator’s information.
- Click on the “Channels” link in the navigation bar.
- Click the “Connect Twilio” button. TextIt makes it easy to integrate with Twilio.
- Enter the SID and Account Token from your Twilo account.

![twilio integration screenshot](/img/textit_token.png)

- [get phone number]
- [Add credits]
- Remember to keep track of your log-in credentials. You’ll want to share it with anyone who will be sending out messages in the future.


Next, learn more about TextIt by watching this quick video. You can always learn more by watching their [training videos](http://textit.in/video/) and reading their [comprehensive documentation](http://docs.textit.in/).

<iframe src="https://player.vimeo.com/video/72253940" width="640" height="360" frameborder="0" webkitallowfullscreen="" mozallowfullscreen="" allowfullscreen=""></iframe>

[Introducing TextIt](https://vimeo.com/72253940) from [TextIt](https://vimeo.com/textitin) on [Vimeo](https://vimeo.com).

## Creating flows in TextIt

Now, it’s time to set up a test campaign. TextIt calls each diagram of a text campaign a “Flow.” Click from the homepage to see sample flows and get a feel for the structure. Then follow the steps below to set up a new flow:

1. Click to create a new Flow
2. Give your Flow a name - for example, “May 2016 Appointment Reminders” 
3. Keep the ‘Keyword Triggers’ field blank 
4. Change the ‘Remove Expired Contacts’ option to “Never” 
5. Keep it as “Run flow over messaging”

Now you can create your first message. Enter the text for what you want to send as the first text message people receive (we’ll go over best practices later). Then, follow the same steps as you saw in the Introduction Video to build your whole flow.

One trick: you can use set up alerts for yourself when someone replies or unsubscribes. Just add a new message for people who arrive at a certain point of your flow and select the option to send an SMS or email to someone else.

![Creating a notice when someone unsubscribes](/img/setup_unsubscribe-notice.png)

Our team set alerts to let us know when someone responded to a text we sent them, so we knew to log in to TextIt and personally respond to their questions.

## Testing your campaign

TextIt has a [built in simulator](http://feedback.textit.in/knowledgebase/articles/776505-using-the-simulator). You can use it to see how messages will appear on a phone, right in your browser.

<iframe width="560" height="315" src="https://www.youtube.com/embed/--PvzMpiWFw" frameborder="0" allowfullscreen=""></iframe>

After you test using the simulator, it's wise to test on a real phone as well. This is a good opportunity to confirm that everything's working, and catch last minute typos. To do that, you will add your own number as an option on the Contacts page and then select your contact when starting a flow.

## Final set up

Before logging out of TextIt, you will want to connect your Twilio and TextIt accounts so you can send text messages with a real phone number. Do that by clicking the [Channels option](https://textit.in/channels/channel/claim/#) on TextIt and following the instructions to connect your Twilio account.
