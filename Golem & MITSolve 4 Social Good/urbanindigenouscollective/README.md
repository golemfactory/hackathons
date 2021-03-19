## ShockTalk

### Email address *

austin@urbanindigenouscollective.org

### Link to your MIT Solve solution *

MIT Page: https://solve.mit.edu/challenges/2020-indigenous-communities-fellowship/solutions/33128

UIC Project Page: https://urbanindigenouscollective.org/project-overview

### Can you describe your organization in less than 200 words? *

ShockTalk seeks to decrease adverse mental health effects attributed to unresolved historical and intergenerational trauma in Native American and Alaska Natives (NA/AN) by connecting users to Native therapists trained and experienced in cultural humility. 

### Do you have a prototype/mock up? If so, please past here the link (If you don't have it, don't worry, email costanza@golem.network and we'll help you with this step)

Private Alpha MVP (current)
https://drive.google.com/file/d/1IUlhF4CAiZVQ4_DJu3O_vqeNO0Tn6FY7/view?usp=sharing

Prototype Vision for React Native Beta (Pending Public Beta Insights — Fall 2021/Winter 2022):
http://austinserio.com/shocktalk/prototype/

### Can you describe what type of app/computation you need? (If you can't answer, don't worry, email costanza@golem.network and we'll help you with this step)

I need some help getting our private alpha MVP over the line to a public beta MVP ready state.

We are beginning with an AI Chatbot assisted concierge service through Facebook Messenger, a popular space for Indigenous communities. Beginning with New York State as our initial service area, users will be able to connect with Shockoe AI through Facebook Messenger to schedule a culturally-tailored matching appointment with the next available Indigenous social worker. 

Shockoe AI is powered by ManyChat and logged through Zendesk. When creating an appointment via Messenger, the user receives a Calendly Team link which delegates the user’s appointment in a round-robin optimized for whichever Indigenous social worker has the most availability. Then, Zapier assigns the Zendesk Ticket, containing the user’s current Facebook conversation, to the social worker delegated by Calendly. In other words, Calendly delegates the Facebook conversation via Zendesk to the next available social worker. During the matching session, the social worker is then able to send the individual Calendly link for the provider in our network that the social worker determines is the best fit for the user. The social worker determines the provider which would be the best fit through a series of questions created and vetted through our 70 person customer discovery proccess across Indian Country, and reviewed by our first Indigneous clinician Shelby Remillard. The social worker sends the Calendly link of the matched therapist directly to the user in Messenger through the Zendesk+Messenger ticket.

We are using Zapier to draft and rapidly iterate the API calls which powers our MVP. API calls are generally triggered by Calendly events, and access Zendesk, GCal, and ManyChat.

### what's the best way for hackers to contact you? *

Shoot me an email! austin@urbanindigenouscollective.org
