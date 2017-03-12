tutorial: https://developer.amazon.com/alexa-skills-kit/alexa-skill-quick-start-tutorial

# 1. Design Voice User Interface

## Mapping b/w user input & intents (things handled by cloud-based service)

Need

1. **Intent Schema**

 - JSON structure that declares set of intents your service can accept & process

2. **Spoken Input Data**

 - Sample Utterances: Structured text file, connects intents to likely spoken phrases. Containing as many representative  phrases as possible.

of form:

<IntentName> phrase_in_lower_case

i.e.

WhatMyColourIntent what is my favourate color

WhatMyColourIntent whats my favourate color

WhatMyColourIntent my color

WhatMyColourIntent my fav color

maps all these phrases to the intent WhatMyColourIntent

- Custom Values: Representative list of values for specific items used by skill and reference in intents when using a custom slot type.

### Intent Schema

- Intent represents an action that fulfills a users request. 
 
- Can have arguments called slots.

- 

