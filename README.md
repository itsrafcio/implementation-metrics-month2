# Implementation Metrics – Month 2

This project demonstrates practical API, Postman, Python and pandas skills in the context of software implementation and delivery.

## Project Scope

The project uses implementation project data covering customers, projects, milestones and costs.

The analysis focuses on practical delivery metrics such as:
- project status distribution
- total project cost
- budget utilization
- overdue unfinished milestones

## Tools and Skills

- Python
- pandas
- CSV data processing
- DataFrame filtering and aggregation
- pandas merge and join cardinality
- API fundamentals
- Postman
- HTTP methods: GET, POST, PUT, PATCH, DELETE
- path and query parameters
- JSON
- environment variables

## Repository Structure

- `data/` – source CSV files
- `notebooks/` – pandas analysis
- `output/` – generated project metrics report
- `api/` – exported Postman collection and environment

## Output

The final project report contains one row per project with:
- project name
- status
- budget
- total cost
- budget utilization
- overdue milestones

## Notes

The API exercises use DummyJSON as a public test API. Create, update and delete operations are simulated by the service.