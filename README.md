# django-allauth-bootstrap5-templates
Bootstrap templates for django-allauth

Wonderful [django-allauth](https://github.com/pennersr/django-allauth) templates are not really friendly with bootstrap.

This repository contains bootstrapped templates by [django-bootstrap5](https://github.com/zostera/django-bootstrap5) for django-allouth.

Requirements:
```bash
pip install django-allauth django-bootstrap5
```

Clone the repository or [download](https://stackoverflow.com/questions/7106012/download-a-single-folder-or-directory-from-a-github-repo) `account` directory

To use the templates just copy `account` directory into your templates folder like this:

```
templates
├── account
│   ├── account_inactive.html
│   ├── base.html
│   ├── email
│   │   ├── base_message.txt
│   │   ├── email_confirmation_message.txt
│   │   ├── email_confirmation_signup_message.txt
│   │   ├── email_confirmation_signup_subject.txt
│   │   ├── email_confirmation_subject.txt
│   │   ├── password_reset_key_message.txt
│   │   └── password_reset_key_subject.txt
│   ├── email.html
│   ├── email_confirm.html
│   ├── footer.html
│   ├── header.html
│   ├── login.html
│   ├── logout.html
│   ├── messages
│   │   ├── cannot_delete_primary_email.txt
│   │   ├── email_confirmation_sent.txt
│   │   ├── email_confirmed.txt
│   │   ├── email_deleted.txt
│   │   ├── logged_in.txt
│   │   ├── logged_out.txt
│   │   ├── password_changed.txt
│   │   ├── password_set.txt
│   │   ├── primary_email_set.txt
│   │   └── unverified_primary_email.txt
│   ├── password_change.html
│   ├── password_reset.html
│   ├── password_reset_done.html
│   ├── password_reset_from_key.html
│   ├── password_reset_from_key_done.html
│   ├── password_set.html
│   ├── signup.html
│   ├── signup_closed.html
│   ├── snippets
│   │   └── already_logged_in.html
│   ├── verification_sent.html
│   └── verified_email_required.html
└── base.html
```

Then feel free to modify the templates and enjoy the result :art:

![bootstrap_image](https://user-images.githubusercontent.com/23726173/124335432-e9e1b400-dba2-11eb-9341-a3e0813a8a2b.png)
