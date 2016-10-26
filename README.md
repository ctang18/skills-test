# Web Development Skills Test

Small HTML, JS, CSS skills test

## Task

For this task, we would like you to rapidly prototype a form where a potential customer can contact a sales representative. 
Upon form submission, the page awlays redirects to the same thank you page URL, but the page should have different messaging depending 
on the number of employees the user submits. If they have 1-49 employees, the message should say "Mike will be in contact with you shortly!"
If they have 50+ employees, the thank you message should say "Sam will be in contact with you shortly!" Ideally, we don't want to let users
think they are getting different levels of treatment, so an average user should not be able to tell that we send them different messaging based on their number of employees.

In practice, the form would be provided by a third party, so it should be considered immutable except for its styling.
This means that you cannot use the typical form "post" method of passing information between pages. 
You can implement multiple different solutions if you can think of them, but don't use any external libraries except for jQuery for the functional 
portion of the task. Do not add any other pages -- all the page links can remain as empty simple placeholders.

The styling is very rough and should be brought up to a more reasonable level, but don't spend too much time on it as this is secondary to the functional portion.
We encourage you to be creative with updating the style and layout as you wish and not worry about it being perfect.
Feel free to note down design ideas that are outside the scope of this task or use external stylesheets and packages for speed.