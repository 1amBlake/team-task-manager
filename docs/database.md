# Entity
- User 
	├── id 
	├── username 
	├── passwordHash 
	└── createdAt

- Category 
	├── id 
	├── name 
	└── userId

- Task 
	├── id 
	├── userId 
	├── categoryId 
	├── title 
	├── description 
	├── priority
	├── status
	├── deadline 
	└── createdAt

# Cardinary
User 1 ───── N Task

User 1 ───── N Category

Category 1 ───── N Task

# Enums
- Status
	- TODO
	- IN_PROGRESS
	- DONE
- Priority
	- LOW
	- MEDIUM
	- HIGH