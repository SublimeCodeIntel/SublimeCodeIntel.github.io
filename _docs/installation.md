---
title: Installation
---

Getting {{ site.name }} installed and ready-to-go should only take a few minutes.
If it ever becomes a pain, please [file an issue]({{ site.repository }}/issues/new)
(or submit a pull request) describing the issue you encountered and how
we might make the process easier.

---

## 1. Install CodeIntel

In order to use SublimeCodeIntel, you need to have CodeIntel installed. CodeIntel
is the engine behind SublimeCodeIntel, and it requires Python 2 or Python 3 to
be installed: Python can be downloaded [here](https://www.python.org/downloads/).

Once Python is available, the easiest way to install CodeIntel is
using the `pip` command:

```sh
~ $ pip install -U CodeIntel
```

---


## 2. Install SublimeCodeIntel

### With the Package Control

The easiest way to install SublimeCodeIntel is through Package Control, which
can be found [here](https://packagecontrol.io/installation).

Once you install Package Control, restart ST2 and bring up the Command Palette
(Command+Shift+P on OS X, Control+Shift+P on Linux/Windows). Select
"Package Control: Install Package", wait while Package Control fetches the
latest package list, then select SublimeCodeIntel when the list appears. The
advantage of using this method is that Package Control will automatically keep
SublimeCodeIntel up to date with the latest version.

### Without Git

Download the latest source from [GitHub]({{ site.repository }}) and copy the
whole directory into the Packages directory.


### With Git
Clone the repository in your Sublime Text Packages directory, located somewhere
in user's "Home" directory:

```sh
~ $ git clone git://github.com/SublimeCodeIntel/SublimeCodeIntel.git
```

The "Packages" packages directory is located differently in different platforms.
To access the directory use:

* **OS X** - `Sublime Text -> Preferences -> Browse Packages...`
* **Linux** - `Preferences -> Browse Packages...`
* **Windows** - `Preferences -> Browse Packages...`

---


## 3. Donate

Development of *SublimeCodeIntel* is done as an open-source project and
maintaining it is hard and time consuming, if you like SublimeCodeIntel, please
donate whatever you feel comfortable with via PayPal. The donations will be
directly used to support SublimeCodeIntel's developers.

<a class="paypalme" href="https://www.paypal.me/Kronuz/20" target="_blank" rel="nofollow">Donate to Kronuz via PayPal</a>
