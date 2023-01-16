# notification
Notification api to send email and sms
## End points are post methods as:
1. /notifications/email
2. /notifications/sms
3. /notifications/all
## Sample request body:
{"to":"mailamrendrakumar@gmail.com",
"emailTemplate":"welcomeEmail",
"context": {"username":"Amrendra"
}
}
