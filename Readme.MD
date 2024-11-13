# Full Stack Developer Technical Challenge

## Objective
Create a Rick and Morty character search engine with cloud infrastructure, backend API, and frontend interface.

## Deadline
The implementation should not take more than a few hours. We would expect that you can solve this in one weekend. And submit by the next Monday.

## Part 1: Cloud Infrastructure (GCP + Terraform)

### Requirements:
- Create Terraform configuration for MongoDB Community Edition deployment on GCP
- Configure and attach block storage
- Implement automated backup solution
- Set up firewall rules to protect the instance
- Destroy and restore with old data

### Evaluation Criteria:
- Clean readable Terraform code
- Successful implementation of backup and restore functionality
- Proper security measures
- Infrastructure scalability considerations

## Part 2: Backend (Go)

### Requirements:
- Build a REST API using Go
- Integrate with the Rick and Morty API (https://rickandmortyapi.com/api/character/)
- Implement character search functionality
- Create endpoints to fetch episode numbers by character names
- Store and retrieve data using MongoDB

### Evaluation Criteria:
- Clean code architecture
- Error handling

## Part 3: Frontend (React + TypeScript)

### Requirements:
- Display character details and associated episode numbers
- Handle loading and error states
- Add basic styling

### Evaluation Criteria:
- TypeScript implementation
- Component structure
- State management
- Code organization

## Bonus Points:
- Implementing caching
- Adding pagination
- UI/UX considerations
- Performance optimizations

## Submission Guidelines:
1. Create a public GitHub repository
2. Include README.md with:
   - Setup instructions
   - API documentation
   - Architecture overview
   - Testing instructions
3. Separate your code into appropriate directories:
   - /terraform
   - /backend
   - /frontend
4. Always use pull requests to merge your code into the main branch.
5. Always squash commits while merging the PR.
5. Do not force push.
6. Do not fork this repo or link it in anyway to your solution.
7. Submit a link to your solution repo as a response to the email.

## Notes:
- Focus on the MongoDB implementation first
- Backend as second, and Frontend as last
- Once the MongoDB setup is built and tested, you may destroy it to save cloud costs.
- Follow clean code principles
- Implement error handling
- Follow best practices for each technology
- Keep commit history clean and meaningful
- Partial submissions are also acceptable, however, it is important to stick to the timeline.
- During the interview you shall be expected to present the entire setup and answer questions.

Please create an Issue on this repository if have any questions about the requirements.

Good luck!
