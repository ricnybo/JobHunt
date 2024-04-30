# Job Hunt 
#### by Richard Nybo
This application facilitates a streamlined job search experience within the United States. Users can customize their search based on job title, employment type (full-time, part-time, or contractor). The search functionality is powered by JSearch, a robust API provided by OpenWeb Ninja, available on RapidAPI.

In addition to providing comprehensive job details, the application also features an 'Apply' button for each job listing. Clicking this button will conveniently redirect the user to the respective job posting in a web browser, enabling a seamless application process.

**.env required to make JSearch API calls!**

Create a .env file at the root and include your Jsearch RapidAPI key for the varible:
* RAPID_API_KEY='yourKey'
## To do
Other backend services have not been implemented. Backend serrvices to be implemented:
* User account login / create
* User profile configuration
* User favorite jobs selection
* Menu list / functionality
* Logout

More items could be added for additional funtionality such as:
* Improved searching to include city
* Improved searching to include distance radius from an address or zip code
* Ability sto search other countries


## Future Enhancements

1. **User Authentication:** Implement a user authentication system to allow users to save their job searches and application history.

2. **Job Alerts:** Add a feature to send users notifications when new jobs matching their search criteria are posted.

3. **Company Reviews:** Integrate a company review feature where users can read and write reviews about the companies posting jobs.

4. **Resume Builder:** Include a resume builder tool to help users create professional resumes within the app.

5. **Interview Preparation:** Provide resources for interview preparation, such as common interview questions for specific job roles.
