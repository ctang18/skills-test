# Web Development Skills Test

Small HTML, JS, CSS skills test

## Task

For this task, we would like you to rapidly prototype a form where a potential customer can contact a sales representative. 
Upon form submission, the page awlays redirects to the same thank you page URL, but the page should have different messaging depending 
on the number of employees the user submits. If they have 1-49 employees, the message should say "Mike will be in contact with you shortly!"
If they have 50+ employees, the thank you message should say "Sam will be in contact with you shortly!"

In practice, the form would be provided by a third party, so it should be considered immutable except for its styling.
This means that you cannot use the typical form "post" method of passing information between pages. 
Implement multiple different solutions if you can think of them, but don't use any external libraries except for jQuery for the functional portion of the task.
Do not add any other pages -- all the page links can remain as empty simple placeholders.

The styling is very rough and should be brought up to an reasonable level, but don't spend too much time on it.
We encourage you to be creative with updating the style and layout as you wish and make it responsive and mobile friendly.
However, we do not expect you to take more than 60-90 minutes on the whole task so don't focus on trying to make it perfect.
Feel free to use external stylesheets and packages but try to keep the site still reasonably lightweight.

## Nice To Haves

We don't want to let users think they are getting different levels of treatment, so an average user should not 
be able to tell that we send them different messaging based on their number of employees.