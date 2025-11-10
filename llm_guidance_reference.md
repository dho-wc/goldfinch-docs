%%
As of 2025-11-10 guidance is assembled on the fly with each interview from interview parameters and generative examples.
This is a snapshot view of those generated guides that was corrected and extended for reference.
%%

# LLM QUESTION GUIDANCE REFERENCE
# Generated from sample_questionsV11.json
# Total Questions: 37

================================================================================

## Question 1: client_fullName
Type: text
Text: What is your full legal name?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "What is your full legal name?"
Type: text
Answer Field: client_fullName
Required: REQUIRED
Description: As it appears on legal documents.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_fullName": "<user_answer>"}
Example: {"client_fullName": "John Doe"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 2: client_gender
Type: radio
Text: What is your gender?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "What is your gender?"
Type: radio
Answer Field: client_gender
Required: REQUIRED
Valid Options: ['male', 'female']
Option Details: 'male' = Male, 'female' = Female
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_gender": "<user_answer>"}
Example: {"client_gender": "male"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 3: client_DOB
Type: date
Text: What is your date of birth?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "What is your date of birth?"
Type: date
Answer Field: client_DOB
Required: REQUIRED
Description: Please enter in MM/DD/YYYY format.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_DOB": "<user_answer>"}
Example: {"client_DOB": "10/15/1970"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 4: client_AKA
Type: text
Text: If you go by another name, please provide it here.

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "If you go by another name, please provide it here."
Type: text
Answer Field: client_AKA
Required: OPTIONAL

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_AKA": "<user_answer>"}
Example: {"client_AKA": "user response"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 5: client-address.city
Type: text
Text: City

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "City"
Type: text
Answer Field: client-address.city
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client-address.city": "<user_answer>"}
Example: {"client-address.city": "user response"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 6: client-address.state
Type: select
Text: State

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "State"
Type: select
Answer Field: client-address.state
Required: REQUIRED
Valid Options: ['Alabama', 'Alaska', 'Arizona', 'Arkansas', 'California', 'Colorado', 'Connecticut', 'District of Columbia', 'Delaware', 'Florida', 'Georgia', 'Hawaii', 'Idaho', 'Illinois', 'Indiana', 'Iowa', 'Kansas', 'Kentucky', 'Louisiana', 'Maine', 'Maryland', 'Massachusetts', 'Michigan', 'Minnesota', 'Mississippi', 'Missouri', 'Montana', 'Nebraska', 'Nevada', 'New Hampshire', 'New Jersey', 'New Mexico', 'New York', 'North Carolina', 'North Dakota', 'Ohio', 'Oklahoma', 'Oregon', 'Pennsylvania', 'Rhode Island', 'South Carolina', 'South Dakota', 'Tennessee', 'Texas', 'Utah', 'Vermont', 'Virginia', 'Washington', 'West Virginia', 'Wisconsin', 'Wyoming']
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client-address.state": "<user_answer>"}
Example: {"client-address.state": "Alabama"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 7: client_email
Type: text
Text: What is your email address?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: aboutYou | 20% Complete

NEXT QUESTION:
Q: "What is your email address?"
Type: text
Answer Field: client_email
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_email": "<user_answer>"}
Example: {"client_email": "user response"}

SECTION PROGRESS: aboutYou - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 8: client_maritalStatus
Type: radio
Text: What is your marital status?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "What is your marital status?"
Type: radio
Answer Field: client_maritalStatus
Required: REQUIRED
Valid Options: ['married', 'single', 'divorced', 'widowed']
Option Details: 'married' = Married, 'single' = Never married, 'divorced' = Divorced, 'widowed' = Widowed
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_maritalStatus": "<user_answer>"}
Example: {"client_maritalStatus": "married"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 9: client_DOM
Type: date
Text: When did you get married?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "When did you get married?"
Type: date
Answer Field: client_DOM
Required: REQUIRED
Description: Please enter in MM/DD/YYYY format.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_DOM": "<user_answer>"}
Example: {"client_DOM": "10/15/1970"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 10: spouse_fullName
Type: text
Text: What is your spouse's full name?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "What is your spouse's full name?"
Type: text
Answer Field: spouse_fullName
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"spouse_fullName": "<user_answer>"}
Example: {"spouse_fullName": "John Doe"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 11: spouse_AKA
Type: text
Text: If your spouse goes by another name, please provide it here.

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "If your spouse goes by another name, please provide it here."
Type: text
Answer Field: spouse_AKA
Required: OPTIONAL

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"spouse_AKA": "<user_answer>"}
Example: {"spouse_AKA": "user response"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 12: spouse_gender
Type: radio
Text: What is your spouse's gender?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "What is your spouse's gender?"
Type: radio
Answer Field: spouse_gender
Required: REQUIRED
Valid Options: ['male', 'female']
Option Details: 'male' = Male, 'female' = Female
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"spouse_gender": "<user_answer>"}
Example: {"spouse_gender": "male"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 13: spouse_DOB
Type: date
Text: What is your spouse's date of birth?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "What is your spouse's date of birth?"
Type: date
Answer Field: spouse_DOB
Required: REQUIRED
Description: Please enter in MM/DD/YYYY format.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"spouse_DOB": "<user_answer>"}
Example: {"spouse_DOB": "10/15/1970"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 14: client_hasChildren
Type: radio
Text: Do you have any children?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "Do you have any children?"
Type: radio
Answer Field: client_hasChildren
Required: REQUIRED
Description: Include adult children, deceased children, stepchildren, biological children, and adopted children.
Valid Options: ['yes', 'maybe', 'no']
Option Details: 'yes' = Yes, 'maybe' = Not yet, but might in the future, 'no' = No, and don't expect to have any
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_hasChildren": "<user_answer>"}
Example: {"client_hasChildren": "yes"}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 15: client-children
Type: items
Text: List your children

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourFamily | 20% Complete

NEXT QUESTION:
Q: "List your children"
Type: items
Answer Field: client-children
Required: OPTIONAL
Description: All children identified here will appear as children in your will (and in your spouse's will, if you are married and end up creating a will for your spouse).
This is a multi-part question with 3 parts:
  1. client-children.fullName: Child's full name
  2. client-children.DOB: Date of birth
  3. client-children.whose: Whose child is this?

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"client-children": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"client-children": [{"client-children.fullName": "value", "client-children.DOB": "value", "client-children.whose": "value"}]}

SECTION PROGRESS: yourFamily - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 16: representatives_incapacity_primary_fullName
Type: text
Text: Representative's full name

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Representative's full name"
Type: text
Answer Field: representatives_incapacity_primary_fullName
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"representatives_incapacity_primary_fullName": "<user_answer>"}
Example: {"representatives_incapacity_primary_fullName": "John Doe"}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 17: representatives-incapacity.hasAlternates
Type: yes-no
Text: Would you like to appoint alternates if the above-named person isn't available?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Would you like to appoint alternates if the above-named person isn't available?"
Type: yes-no
Answer Field: representatives-incapacity.hasAlternates
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"representatives-incapacity.hasAlternates": "<user_answer>"}
IMPORTANT: Convert user's yes/no response to boolean values: true or false
Example: {"representatives-incapacity.hasAlternates": true} or {"representatives-incapacity.hasAlternates": false}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 18: representatives-incapacity-alternates
Type: items
Text: Add Alternate Representative

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Add Alternate Representative"
Type: items
Answer Field: representatives-incapacity-alternates
Required: OPTIONAL
Description: List their full names in order of preference.
This is a multi-part question with 1 parts:
  1. representatives-incapacity-alternates.fullName: Full name

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"representatives-incapacity-alternates": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"representatives-incapacity-alternates": [{"representatives-incapacity-alternates.fullName": "value"}]}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 19: representatives_afterDeath_primary_fullName
Type: text
Text: Representative's full name

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Representative's full name"
Type: text
Answer Field: representatives_afterDeath_primary_fullName
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"representatives_afterDeath_primary_fullName": "<user_answer>"}
Example: {"representatives_afterDeath_primary_fullName": "John Doe"}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 20: representatives-afterDeath.hasAlternates
Type: yes-no
Text: Would you like to appoint alternates if the above-named person isn't available?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Would you like to appoint alternates if the above-named person isn't available?"
Type: yes-no
Answer Field: representatives-afterDeath.hasAlternates
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"representatives-afterDeath.hasAlternates": "<user_answer>"}
IMPORTANT: Convert user's yes/no response to boolean values: true or false
Example: {"representatives-afterDeath.hasAlternates": true} or {"representatives-afterDeath.hasAlternates": false}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 21: representatives-afterDeath-alternates
Type: items
Text: Add Alternate Representative

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Add Alternate Representative"
Type: items
Answer Field: representatives-afterDeath-alternates
Required: OPTIONAL
Description: List their full names in order of preference.
This is a multi-part question with 1 parts:
  1. representatives-afterDeath-alternates.fullName: Full name

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"representatives-afterDeath-alternates": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"representatives-afterDeath-alternates": [{"representatives-afterDeath-alternates.fullName": "value"}]}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 22: representatives_healthcare_primary_fullName
Type: text
Text: Representative's full name

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Representative's full name"
Type: text
Answer Field: representatives_healthcare_primary_fullName
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"representatives_healthcare_primary_fullName": "<user_answer>"}
Example: {"representatives_healthcare_primary_fullName": "John Doe"}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 23: representatives-healthcare.hasAlternates
Type: yes-no
Text: Would you like to appoint alternates if the above-named person isn't available?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Would you like to appoint alternates if the above-named person isn't available?"
Type: yes-no
Answer Field: representatives-healthcare.hasAlternates
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"representatives-healthcare.hasAlternates": "<user_answer>"}
IMPORTANT: Convert user's yes/no response to boolean values: true or false
Example: {"representatives-healthcare.hasAlternates": true} or {"representatives-healthcare.hasAlternates": false}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 24: representatives-healthcare-alternates
Type: items
Text: Add Alternate Representative

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourRepresentatives | 20% Complete

NEXT QUESTION:
Q: "Add Alternate Representative"
Type: items
Answer Field: representatives-healthcare-alternates
Required: OPTIONAL
Description: List their full names in order of preference.
This is a multi-part question with 1 parts:
  1. representatives-healthcare-alternates.fullName: Full name

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"representatives-healthcare-alternates": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"representatives-healthcare-alternates": [{"representatives-healthcare-alternates.fullName": "value"}]}

SECTION PROGRESS: yourRepresentatives - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 25: guardiansForChildren_hasGuardians
Type: yes-no
Text: Would you like to appoint a guardian for your children?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Would you like to appoint a guardian for your children?"
Type: yes-no
Answer Field: guardiansForChildren_hasGuardians
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"guardiansForChildren_hasGuardians": "<user_answer>"}
IMPORTANT: Convert user's yes/no response to boolean values: true or false
Example: {"guardiansForChildren_hasGuardians": true} or {"guardiansForChildren_hasGuardians": false}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 26: guardiansForChildren-guardians
Type: items
Text: Identify guardians for your children

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Identify guardians for your children"
Type: items
Answer Field: guardiansForChildren-guardians
Required: OPTIONAL
Description: List your guardians in order of preference.
This is a multi-part question with 1 parts:
  1. guardiansForChildren-guardians.fullName: Full name

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"guardiansForChildren-guardians": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"guardiansForChildren-guardians": [{"guardiansForChildren-guardians.fullName": "value"}]}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 27: client_hasPetProvisions
Type: radio
Text: Do you want to include provisions for the care of pets?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Do you want to include provisions for the care of pets?"
Type: radio
Answer Field: client_hasPetProvisions
Required: REQUIRED
Description: If you have pets when you pass away, these provisions will allow you to appoint a caretaker for your pets and set aside a dollar amount for their care.
Valid Options: ['yesIdentify', 'yesDontIdentify', 'no']
Option Details: 'yesIdentify' = Yes, and identify my pets, 'yesDontIdentify' = Yes, but don't identify my pets, 'no' = No
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_hasPetProvisions": "<user_answer>"}
Example: {"client_hasPetProvisions": "yesIdentify"}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 28: client-pets
Type: items
Text: Identify your pets

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Identify your pets"
Type: items
Answer Field: client-pets
Required: OPTIONAL
This is a multi-part question with 2 parts:
  1. client-pets.name: Pet's name
  2. client-pets.type: Type of pet

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"client-pets": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"client-pets": [{"client-pets.name": "value", "client-pets.type": "value"}]}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 29: client_petsCaretaker
Type: text
Text: Who do you want to take care of your pets?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Who do you want to take care of your pets?"
Type: text
Answer Field: client_petsCaretaker
Required: REQUIRED
Description: Pet caretaker's full name

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_petsCaretaker": "<user_answer>"}
Example: {"client_petsCaretaker": "user response"}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 30: client_petsCareAmount
Type: text
Text: How much would you like to allocate for their care?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "How much would you like to allocate for their care?"
Type: text
Answer Field: client_petsCareAmount
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"client_petsCareAmount": "<user_answer>"}
Example: {"client_petsCareAmount": "user response"}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 31: maintainInHome
Type: yes-no
Text: Do you want in-home assisted living or nursing care?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Do you want in-home assisted living or nursing care?"
Type: yes-no
Answer Field: maintainInHome
Required: REQUIRED
Description: Answer yes if you want assisted living or nursing care, including round-the-clock care, to be provided in your home if it's reasonable to do so under the circumstances.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"maintainInHome": "<user_answer>"}
IMPORTANT: Convert user's yes/no response to boolean values: true or false
Example: {"maintainInHome": true} or {"maintainInHome": false}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 32: remainsPreference
Type: radio
Text: Do you have any preference for handling your remains?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: yourWishes | 20% Complete

NEXT QUESTION:
Q: "Do you have any preference for handling your remains?"
Type: radio
Answer Field: remainsPreference
Required: REQUIRED
Valid Options: ['cremation', 'burial', 'no-preference']
Option Details: 'cremation' = Cremation, 'burial' = Burial, 'no-preference' = No preference
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"remainsPreference": "<user_answer>"}
Example: {"remainsPreference": "cremation"}

SECTION PROGRESS: yourWishes - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 33: hasSpecificGifts
Type: yes-no
Text: Would you like to leave gifts of specific items or dollar amounts to anyone?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: estateDistribution | 20% Complete

NEXT QUESTION:
Q: "Would you like to leave gifts of specific items or dollar amounts to anyone?"
Type: yes-no
Answer Field: hasSpecificGifts
Required: REQUIRED

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"hasSpecificGifts": "<user_answer>"}
IMPORTANT: Convert user's yes/no response to boolean values: true or false
Example: {"hasSpecificGifts": true} or {"hasSpecificGifts": false}

SECTION PROGRESS: estateDistribution - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 34: specificGifts
Type: items
Text: Please describe what you would like to leave and to whom.

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: estateDistribution | 20% Complete

NEXT QUESTION:
Q: "Please describe what you would like to leave and to whom."
Type: items
Answer Field: specificGifts
Required: OPTIONAL
This is a multi-part question with 3 parts:
  1. specificGifts.description: Describe the gift
  2. specificGifts.name: Who would you like to leave this gift to?
  3. specificGifts.type: Is this beneficiary an individual or charitable organization?

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"specificGifts": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"specificGifts": [{"specificGifts.description": "value", "specificGifts.name": "value", "specificGifts.type": "value"}]}

SECTION PROGRESS: estateDistribution - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 35: residuaryDistribution
Type: radio
Text: How would you like to distribute the remainder of your estate?

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: estateDistribution | 20% Complete

NEXT QUESTION:
Q: "How would you like to distribute the remainder of your estate?"
Type: radio
Answer Field: residuaryDistribution
Required: REQUIRED
Description: If you are married, the remainder of your estate will go to your spouse. If you are not married, or if your spouse is deceased, how would you like to distribute the remainder of your estate?
Valid Options: ['children', 'named']
Option Details: 'children' = To my children, 'named' = To named beneficiaries
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"residuaryDistribution": "<user_answer>"}
Example: {"residuaryDistribution": "children"}

SECTION PROGRESS: estateDistribution - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 36: residuaryNamedBeneficiaries
Type: items
Text: Please specify the named beneficiaries and the shares they should receive.

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: estateDistribution | 20% Complete

NEXT QUESTION:
Q: "Please specify the named beneficiaries and the shares they should receive."
Type: items
Answer Field: residuaryNamedBeneficiaries
Required: OPTIONAL
This is a multi-part question with 2 parts:
  1. residuaryNamedBeneficiaries.name: Beneficiary name
  2. residuaryNamedBeneficiaries.share: Share of the estate

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Array format: Use container-field format
Record as: {"residuaryNamedBeneficiaries": [{"field": "value"}, ...]}
Object structure inside array:
Example: {"residuaryNamedBeneficiaries": [{"residuaryNamedBeneficiaries.name": "value", "residuaryNamedBeneficiaries.share": "value"}]}

SECTION PROGRESS: estateDistribution - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------

## Question 37: specialSituations
Type: checkbox
Text: Indicate if any of the following special situations apply to you.

### LLM Guidance:
```
INTERVIEW STATE: Active | Section: specialSituations | 20% Complete

NEXT QUESTION:
Q: "Indicate if any of the following special situations apply to you."
Type: checkbox
Answer Field: specialSituations
Required: OPTIONAL
Description: We will include a document in your package about these special situations, highlighting the ones that apply to you.
Valid Options: ['underageBenes', 'stepchildren', 'specialNeedsBenes', 'adoptedDescendants', 'nonCitizenSpouse', 'obligationsFromPriorMarriage', 'businessOrRentalProperty', 'foreignAssets', 'protectAssets', 'concernsAboutDeathTaxes']
Option Details: 'underageBenes' = I have underage beneficiaries, 'stepchildren' = I have stepchildren, 'specialNeedsBenes' = I have a beneficiary with special needs, 'adoptedDescendants' = I have descendants adopted out of the family, 'nonCitizenSpouse' = I have a noncitizen spouse, 'obligationsFromPriorMarriage' = I have obligations from a prior marriage, 'businessOrRentalProperty' = I own a business or rental property, 'foreignAssets' = I own foreign assets, 'protectAssets' = I want to protect assets from creditors, 'concernsAboutDeathTaxes' = I am concerned about death taxes
IMPORTANT: You must map the user's response to one of the valid option values above. If the user's answer doesn't clearly match any option, ask for clarification before proceeding.

ANSWER STRUCTURE:
IMPORTANT: Use the exact Answer Field ID shown above.
Record as: {"specialSituations": "<user_answer>"}
Example: {"specialSituations": "user response"}

SECTION PROGRESS: specialSituations - 1/5

READINESS: PRESENTING_QUESTIONS - Continue asking questions
```

--------------------------------------------------------------------------------