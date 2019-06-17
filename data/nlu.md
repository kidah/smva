## intent:greet
- hey
- hello
- hi
- good morning
- good evening
- hey there
- hi bot
- howdy
- hola

## intent:goodbye
- bye
- goodbye  
- see you around
- see you later
- ciao
- ttyl
- gtg
- adios
- farewell
- adieu
- chao
- chau
- got to go
- i've got to go
- leaving
- talk to you soon
- have to go
- got to go
- talk to you later
- heading out
- im leaving now
- going out


## intent:affirm
- yes
- indeed
- of course
- that sounds good
- correct

## intent:deny
- no
- never
- I don't think so
- don't like that
- no way
- not really

## intent:mood_great
- perfect
- very good
- great
- amazing
- wonderful
- I am feeling very good
- I am great
- I'm good

## intent:mood_unhappy
- sad
- very sad
- unhappy
- bad
- very bad
- awful
- terrible
- not very good
- extremely sad
- so sad

## intent:thank
- thanks
- thank you
- thank you very much
- gracias
- thank

## intent:search_bot
- what is your [name](name)
- tell me your [name](name)
- who do you [work](employer) for 
- who is your [employer](employer)
- what is your best [food](food)
- what is your favorite [food](food)
- what is your favorite [movie](movie)
- what is your best [movie](movie)
- what is your favorite [book](book)
- what is your best [book](book)

## intent:joke
- tell me a joke
- could you tell me a joke
- tell me something funny
- could you please brighten my day
- say something funny
- please make me laugh
- i want to hear a joke

## intent:news
- could you tell me some news
- could you read me some construction news
- tell me the latest internal company news
- give me the latest company news

## intent:manager_calender
- could you confirm the activities on my calendar for [today](date)
- could you tell me the actvities i have on my calender for this [morning](date)
- what activities do i have on my calender for [next week](date)
- am i free by [1pm tomorrow](date)

## intent:project_information
- what is the project [title](title)
- when is the [start date](start_date) of the project 
- when is the [end date](end_date) of the project
- tell me the [start date](start_date) of the project 
- tell me the [end date](end_date) of the project
- what is the project [location](location)
- what is the [contract type](contract_type)
- tell me the [contract type](contract_type)
- what is the [construction type](construction_type) of the project
- tell me the [construction type](construction_type) of the project
- what is the [cost](cost) of the project
- what is the [value](cost) of the project
- what is the [duration](duration) of the project
- tell me the [duration](duration) of the project
- what is the [job number](project_code) of the project
- tell me the [project code](project_code)
- which [business unit](business_unit) is in charge of the project
- what [business unit](business_unit) is in charge of the project
- what are the [nominal hours](nominal_hours) of the project
- tell me the [nominal hours](nominal_hours) of the project
- what [season](season) is this project taking place
- which [season](season) is this project taking place

## intent:search_project_activities
- which project activities are due [next week](date)
- could you please confirm the activities for [this week](date)
- can you confirm the [start](planned_start_date) and [end](planned_end_date) date for those activities
- confirm the activities for [this week](date)
- when is the [start date](planned_start_date) for [EXCJB1](activity_code)
- could you confirm the [end date](planned_end_date) for [EXCJB4](activity_code)
- what are the activities in [EXCJB5]
- when is the [end date](planned_end_date) for that activity
- what is the [start date](planned_start_date) for that activity
- is there a [lag](lag) for that activity?
- how many days [lag](lag)?
- tell me the planned start date of [EXCJB1](activity_code)
- tell me the actual [end date](actual_end_date) of [EXCJB2](activity_code)
- tell me the [duration](planned_duration) of [EXCJB3](activity_code)
- what is the [duration](planned_duration) of [EXCJB1](activity_code)
- [how long](planned_duration) will it take to complete [EXCJB6](activity_code)
- what was the [actual start date](actual_start_date) of [EXCJB1](activity_code)
- what was the [actual start date](actual_start_date) of [EXCJB2](activity_code)
- what was the [actual end date](actual_end_date) of [EXCJB2](activity_code)
- what was the [actual end date](actual_end_date) of [EXCJB3](activity_code)
- [how long](planned_duration) will it take to complete that activity
- [how long](actual_duration) did it take to complete [EXCJB6](activity_code)
- [how long](actual_duration) did it take to complete [EXCJB7](activity_code)
- what was the [actual duration](actual_duration) of [EXCJB3](activity_code)
- what was the [actual duration](actual_duration) of [EXCJB2](activity_code)
- do I have any [floats](float) for this activity
- do I have any [float](float)
- do I have any [floats](float) [next week](date) 
- tell me the [variation](variation) between the planned and actual dates for [EXCJB1](activity_code)
- tell me the [variance](variation) between the planned and actual dates for [EXCJB5](activity_code)

## intent:enter_data
- [EXCJB1](activity_code)
- [EXCJB2](activity_code)
- [EXCJB3](activity_code)
- [EXCJB4](activity_code)
- [EXCJB5](activity_code)
- [EXCJB6](activity_code)
- [EXCJB7](activity_code)
- [EXCJB8](activity_code)
- [Route1001](activity_code)
- [Route1002](activity_code)
- [Route1003](activity_code)
- [Route1004](activity_code)
- [Route1005](activity_code)
- [Route1006](activity_code)
- [29th of June](date)
- [14th of March](date)
- [17th of May](date)
- [23rd of August](date)
- [2nd of February, 2017](date)
- [6th of January](date)
- [10th of April, 2016](date)
- [21st of July](date)
- [7th of November](date)
- [9th of October](date)
- [29th of December](date)
- [2nd of September, 2019](date)
- [3rd of April, 2018](date)
- [2/10/2019](date)
- [3/11/2020](date)
- [12/06/2017](date)

## intent:create_issue
- create an issue
- log an issue
- i want to log an issue
- i want to create an issue

##intent:search_issues
- are there any [open](status) issues
- tell me the [open][status] issues
- tell me the [rejected](status) issues
- tell me the [answered](status) issues
- tell me the [rejected](status) issues
- tell me the [open](status) issues this week
- search for any [open](status) issues
- are there any [unresolved](status) issues during this week
- tell me about the [door schedule](title) issue
- tell me about the [Stair 2 Level 2 landing conflict](title) issue
- tell me about the [Need detailed specification for wall covering](title) issue
- who was it [assigned to](assigned_to)
- who was the issue [assigned](assigned_to) to
- who [created](owner) the issue 
- who [created](owner) the issue
- what is the [type](type) of the issue
- what is the issue[type](type)
- what is the [due date](due_date) of the issue
- tell me the [due date](due_date) of the issue
- what is the [location](location) of the issue

## intent:update_progress
- I would like to update project progress
- i want to update project progress
- update project progress
- update activity progress

##intent:search_materials
- give me a list of the [materials](material) needed for this project
- tell me the [route](route) and [quantity](quantity) for cable
- tell me the routes[routes] for the cables
- tell me the [quantity](quantity) of ducts
- tell me the materials needed to carry out [Route1003](route)
- tell me the [routes](route) the [cable](material) material will be used for
- tell me the [quantity](quantity) of [cables](material) bought for next week's activities

##intent:search_people
- who is the responsible for [EXCJB5](activity_code)
- who is the subcontractor incharge of [EXCJB6](activity_code)
- who is the contractor responsible for [excavation](activity) activies
- who is responsible for [cabling](activity) activities

##intent:search_project_information
- tell me the title of the project
- tell me the project code
- what are the normal work hours
- tell me the season
- tell me the weather
- tell me the season and weather

##intent:search_earlywarnings
- are there any early warnings
- are there any early warnings for these activities
- tell me the early warnings for this project
- are there any early warnings for that activity

##intent:lookup_acceleration
- can I accelerate the activities for [EXCJB4](activity_code)
- [how many](available_days) days do I have to accelerate tasks
- [how many](available_days) days do I have to accelerate the [excavation](activity) tasks 
- which weekend is [free, sunny, not sunny](weather)
- what is the [weather](weather) like in the [available period](available_days)
- could you please put it down as a working day
- does that have any effect on the other activities
- I want to accelerate

##intent:search_variation
- how long is the [client variation period](client_variation_period)
- what is the [client variation period](client_variation_period)
- are there any variations

##intent:move_dates
- ok, could you move that start date from the [21st of June](from_date) to the [22nd of June](to_date)
- please move the start date from the [29th of June](from_date) to [31st of June](to_date) for [EXCJB3](activity_code)

#intent:estimate_cost
- what is the estimated cost of materials, labour, plant, subcrontactor cost and expenses for those two days
- could you give me an estimated cost of two extra days of work on [EXCJB3](activity_code)


## synonym:favorite
- favorite
- best
- favourite
