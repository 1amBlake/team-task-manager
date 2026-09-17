# Project Overview
## Roadmap
- Phase 1 - Định hình project
- Phase 2 - Thiết kế architecture
- Phase 3 - Setup project
- Phase 4 - Database
- Phase 5 - Core features
- Phase 6 - UI / UX
- Phase 7 - Testing + Cleanup
- Phase 8 - README + Portfolio
- Phase 9 - Backend
- Phase 10 - Mobile

## Process
### Phase 1 
#### Purpose
- TTM là một ứng dụng desktop offline để quản lý nhiệm vụ, tác vụ, công việc của một nhóm nhỏ
- Phạm vi dự án hiện tại chỉ gồm một người sử dụng đơn lẻ, dùng để đánh dấu tiến độ, tạo tiến độ công việc cho nhóm
#### Target Users
- User cá nhân
#### Core Features
- Local Authentication
	- Đăng ký tài khoản local (Sign up)
	- Đăng nhập (Login)
	- Đăng xuất (Logout)
	- Đổi mặt khẩu (Change password - local)
		Account: (username, password)
- Task Management
	- Tạo task (Create task)
	- Xem task (View details)
	- Chỉnh sửa task (Modify task)
	- Xóa task (Delete task)
	- Đánh dấu hoàn thành (Mark as completed)
	- Trạng thái task (Task status)
		Task: (title, description, status, priority, deadline, createdAt, updatedAt)
- Task Organization
	- Category
		- Study
		- Work
		- Personal
		- Other
	- Filter
		- Status
		- Priority
		- Category
		- Search task
	- Deadline & Reminder
		- Due today
		- Overdue
		- Dashboard hiển thống kê
	- Dashboard
		- Tổng task
		- Completed
		- In progress
		- Overdue
		- Completion rate
#### Flows
Login -> Dashboard -> Create task -> Set Priority | Category | Deadline -> Task appears on Dashboard -> Search / Filter -> Mark as in progress -> Mark as done -> Dashboard updates progress
#### Technology
- Desktop
	- Java
	- JavaFX
	- SQLite
	- Maven
#### Future Plan
- Unknown
### Phase 2

#### [[architecture]]
#### [[database]]
#### [[ui-design]]
#### [[user-flow]]

### Phase 3

Create Maven Project
        ↓
JavaFX
        ↓
SQLite JDBC
        ↓
Package structure
        ↓
Run empty JavaFX application