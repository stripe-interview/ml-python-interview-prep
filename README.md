# ML Python Interview Preparation

Thanks for interviewing at Stripe.
To make sure that we can use our time best in the interviews,
we'd like to have you do some setup on your laptop in advance.
If you don't have a laptop, let your recruiter know
and they will supply you with a loaner laptop for your in-person interviews.

First, _clone_ or _download_ this repository to your computer
via the links on the right
(creating a fork of the repository is not necessary).

Note, we will be working with **Python 3** (Python 3.6 or later).
See the [RealPython installation guide], if you haven't installed Python 3 yet.

We'll create a [virtual environment] with [venv]
and install some Python packages that will be useful in your interviews.

**Create a new virtual environment** called `interview_env` and _activate_ it.

```bash
$ python3 -m venv ./interview_env
$ source ./interview_env/bin/activate
```

The `activate` script is for Bash and Zsh on Mac or Linux.
For other shells, such as Fish or Csh, see the [venv] documentation.

On Windows (assuming `cmd.exe`):

```batch
> python -m venv .\interview_env
> .\interview_env\Scripts\activate
```

Next, **install some requirements** into the activated virtual environment:

```bash
(interview_env) $ pip install -r interview_requirements.txt
```

Finally, in that activated virtual environment, verify that we are able to print out versions for requirements without error:

```bash
(interview_env) $ python verify_requirements.py
```

If you see a response that begins with `Error`, follow the instructions it provides.


[RealPython installation guide]: https://realpython.com/installing-python/
[virtual environment]: https://realpython.com/python-virtual-environments-a-primer/
[venv]: https://docs.python.org/3/library/venv.html
[virtualenv]: https://virtualenv.pypa.io/en/latest/installation.html
