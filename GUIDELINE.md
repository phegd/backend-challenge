## Guideline

These are some tips to help you pass this assignment.
We want you to succeed.
In case you don't manage to pass the review, we want you to avoid unnecessary effort since we respect both your effort and your time.

* Provide unit and integration tests: **the solution that does not have tests rarely passes our review**
* Please submit a clean solution
    * No commented code
    * Code must compile
    * Tests are executable
    * Code should be easy to read
    * Better deliver less, but something that works
* Find a way to showcase your skill in scope of the task
  * If you are applying for Senior or Lead position, we expect you to manifest your skills, not merely meet the requirements
* Do not overcomplicate
    * We do not count lines of code, we evaluate the quality of the solution, the smaller it is, the better (yet it has to satisfy task requirements and showcase your skill - it's your task to strike a good balance between meeting requirements and brevity)
    * We value your time and ours. We expect a single Controller, Service, and Repository. Feel free to create as many auxiliary classes as needed.
        * It's ok to have more classes with business logic as long as it is part of the solution and makes code organization better
        * We do not expect many model entities, even one could be enough
    * No need to implement any functionality we didn't ask for in the task description
        * Adding anything extra that is unrelated to the task does not give you points.
        * some candidates submit solutions with 50+ classes - we don't need that. Both a candidate and a reviewer spend extra time on this. If the application does not pass our criteria, both persons waste more time than they should have.
* Make configuration as simple and concise as possible
    * We assess the quality of the programmatic solution, not the configuration
    * Still we expect some minimal reasonable configuration
    * Do:
        * Configure input validation
        * Configure Exceptions
        * Prefer Spring Boot auto-configuration over explicit configuration when applicable
        * Configure anything that you think is common sense
    * Don't:
        * Configure low-level database properties such as pool-size, etc
        * Configure properties not needed in the application: for instance localization
        * Submit configuration files 50+ lines long

