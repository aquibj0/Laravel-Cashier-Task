Steps to Produce

1. Clone the repository
2. Configure database using .env file
3. Run migration
4. Add two environment variables STRIPE_KEY and STRIPE_SECRET for using payment gateway
5. Create two product in stripe dashboard and copy the respective stripe_id of each product and update the PlanSeeder
6. Run DB seeder to seed the Payment Plan data in plans table
7. Go to /plans to choose the plan and follow the steps accordingly to subscribe user 

Thanks.
