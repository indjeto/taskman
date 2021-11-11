# taskman


### Security

Only logged users can access the tasks.

Every user sees all the tasks, but can edit/delete/mark as done only his own tasks.



### Installation

1. Clone the repo
   ```sh
   git clone https://github.com/indjeto/taskman.git
   cd taskman
   ```
2. Run migrations
   ```sh
   php bin/console doctrine:migrations:migrate
   ```
2. Run the app
   ```sh
   symfony serve
   ```

### To Do

1. Docker integration
2. Api for frontend guys to make the UI