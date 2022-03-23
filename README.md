# Typescript technical interview test

Welcome to Tymeshift's typescript code test 🧪

## Task description:
- Implement RESTful API endpoints for following resources
	- Schedule
		- id: uuid
		- account_id: int
		- agent_id: int
		- start_time: DateTime
		- end_time: DateTime
	- Tasks
		- id: uuid
		- account_id: int
		- schedule_id: uuid
		- start_time: DateTime
		- duration: int
		- type: string Enum['break', work]
	Relation is Schedule has many Tasks
- Write unit tests 

## Guidelines 
- Solution should be written in Typescript, use any packages/frameworks of your liking 
- Use SQL based database preferably PostgreSQL 
- You can upload your solution to GitHub or send us a ZIP file with the solution via email (via reply in Breezy)
- We tried to create a task with a small scope but take all the time you need to feel comfortable with your solution and do it at your own pace


## What we're looking for 
- Implement all relative code design patterns that you see fit for this type of CRUD applications
- Try to future proof code base 
- Keep an eye on following SOLID principles 
- At tymeshift we like DDD so ideally you like it too 