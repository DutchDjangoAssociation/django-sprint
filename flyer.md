# Welcome to the Dutch Django sprint 2015!

During this 2-day sprint we'll join forces and contribute to the Django Web
Framework. We hope to work on many tickets and make Django more stable,
advanced, powerful, easier to use, and so on. The Dutch Django Association aims
to do one sprint every year. You can follow us on DjangoVereniging.nl,
Meetup.com and Twitter (@DutchDjango).

A lot has happend to Django since our last sprint back in November, that was
organized a day after the successful *Django: Under The Hood* conference.

*Over here, tell something about what happened to Django lately, stuff like:*

- Django 1.8 alpha release
- Django website redesign
- Success of the fellowship program
- Pluggable template engines
- django.contrib.postgres
- (have a look through the release notes for more)


## How does it work?

Find a spot where you can work comfortably, and contribute to Django in any way
you like! Naturally you can fix bugs or work on new features, but you can also
improve documentation, write missing unit-tests, validate bugs reported by
others,  improve localization or anything else you can think of. The best way
you can contribute is to work on something you're motivated about!

If you've never contributed to Django before, a sprint is a good place to
start. There are lots of people around that are willing to help, including four
core-developers that have deep knowledge of Django. If you have a question,
don't hesitate to ask someone. You can always ask a core developer, but your
neighbour might have the answer as well. You could also ask in the
`#django-sprint` channel on freenode IRC.

It's recommended to start with something easy, like improving the documentation
of a feature you found hard to understand or found to have confusing
documentation. You could try to fix a simple bug. Through this you'll get a
better idea how the contribution process works, and you will be more successful
for your bigger contributions later on. You can work on something by yourself,
team up with others, pair program, or have an occasional good talk with your
fellow Django-enthusiasts! Lunch, dinner, drinks and snacks are provided by the
Dutch Django Association.


## Where do I begin?

### Django's bug tracker

During a sprint, a lot of people are working on Django at the same time. To
prevent people from working on the same issues, we use Django's bug tracker.
Before you start working on a ticket, make sure to assign it to yourself, so
others can see you're on it already. If you want to work on an improvement, but
there is no ticket yet, create one. If a ticket was already assigned to someone
in the past but they don't appear to work on it anymore, feel free to take it.

### Open tickets

There are a lot of open tickets in Django's bug tracker - over a thousand - so
it's sometimes hard to choose what to work on. Use the search and filter
features to look for something you find interesting and appropriate.

For your first contribution to Django, it's recommended to take an **easy
pickings** issue. These issues should be fairly easy to resolve, even if you
don't have a lot of experience with Django or Python.

Some tickets might not be clear to you. Some might have become irrelevant, and
weren't closed for some reason. Some might require more discussion before the
ticket can be acted upon. A sprint is an excellent opportunity to ask questions
and discuss about these kind of things.

### Pull requests and commits

All development on Django is done on GitHub. Code and documentation are part of
the same git repository. Once you have some changes that you think are ready
for review, you push them to your own fork of the repository and create a pull
request (PR). In the PR, note the number and a short description of the ticket,
e.g. `Fixed #1234 -- Clarified ModelForm documentation`.

A second person should then review your contribution. They may get back to you
with suggested improvements or points for discussion. Once review is completed,
the ticket can get a final review from a core developer and may be committed
into Django. Sometimes the first review is directly done by a core developer.


## Let's get started

Fork **github.com/django/django** into your own GitHub account and get a local
clone of your repository. The documentation is also all part of that repo -
translations are managed through Transifex.

Links to the bug tracker, important information about contribution and other
usefull information can be found on
**github.com/DutchDjangoAssociation/django-sprint**. Also join the
`#django-sprint` channel on freenode IRC.

There are four core developers present during the sprint:

- Baptiste Mispelon
- Markus Holtermann
- Daniele Procida
- Erik Romijn

Feel free to come to us with questions and suggestions. You can recognize most
of us by our red Django sprint t-shirts.

Good luck!


## Terminology

### Common ticket statuses and flags

- **New**: a new ticket which has not had any review of another person of whether
  this is a real bug or good feature request
- **Accepted**: a ticket of which the idea/report, but not the code, has been
  reviewed and validated by another contributor
- **Has patch**: a flag that indicates a ticket has a patch (an associated PR)
- **Patch needs improvement**: a flag that the current patch needs more work.
  Details are found in either ticket comments or comments on the PR on GitHub
- **Ready for checkin**: a ticket with a patch that was also reviewed by another
  contributor and is ready for core developer checkin

Generally, if you add a patch to a ticket you should not yourself set it to
Ready for checkin, unless the patch is very trivial.

### Other terms

- **Pull request**: a request on GitHub to contribute changes to the Django
  repository, usually called PR

## Other upcoming Django sprints and events

- **Django Sprint** - Brno, Czech Republic - Februari 8
- **Djangovillage 2015** - During PyCon Italia, Florence, Italy - April 17-19
- **Django Sprint** - London, UK - May 21 & 22
- **DjangoCon Europe 2015** - Cardiff, Wales - May 31 to June 5
