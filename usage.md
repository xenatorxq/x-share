# Facebook Auto Tool v4.2

Hey there! This is the **XSH / XV Tool**, created by ppheruni. It's a casual, easy-to-use script that helps you **share posts and leave comments** automatically on Facebook using your cookies.

**Author :** ppheruni 

**Social :** [Phuri Suthichai](https://facebook.com/xenator.xqt)

**Version :** 4.2

---

## How to Use It

### Step 1: Prep Your Cookies

Save your Facebook cookies in `/sdcard/cookies.txt`, with **one cookie per line**.

### Step 2: Run the Tool

```bash
python xv.py
```

### Step 3: Check Out the Main Menu

```bash
[A] › AUTO SHARE (User can choose what line they want.)
[B] › AUTO COMMENT (All Cookies)
[0] › EXIT
```

---

## AUTO SHARE (Manual Cookie Selection)

1. Pick `[A]` from the main menu.
2. Select the cookie line you want to use.
3. Paste the **Facebook post URL** you want to share.
4. Enter how many shares you want.
5. Set the **delay** between shares (default is `0.5s`).
6. Sit back and watch the progress:

```
Starting shares...
(1 - 5)
(2 - 5)
(3 - 5)
...
Total: 5, Success: 5, Failed: 0, Success Rate: 100.00%
```

Everything will update in real-time, so you can see how many shares are done and how many succeeded.

---

## AUTO COMMENT (Random Cookies)

1. Choose `[B]` from the main menu.
2. Enter the **Facebook post URL**.
3. Type your comments, separated by `|` (pipe) if you want multiple comments rotated, e.g.:

```
I LUV YURI | I AM GAY | LOL
```

4. Enter how many comments you want.
5. Set the **delay** between comments (default is `1s`).
6. Watch the progress:

```
Starting comments...
(1 - 5)
(2 - 5)
(3 - 5)
...
Total: 5, Success: 5, Failed: 0, Success Rate: 100.00%
```

Comments rotate automatically across all your cookies for randomness.

---

## Version 4.2 Features

* **Manual cookie selection** for Auto Share
* **Random cookie selection** for Auto Comment
* Multiple comments supported using `|` separator
* Configurable delay for shares and comments
* Progress and summary display showing successes and failures
* **Auto React removed** because it wasn't working reliably and I’m still working on it

---

> [!NOTE]
> Tips & Notes

* Make sure to use **valid cookies** to avoid failed attempts.
* Keep the **delay reasonable** to reduce risk of Facebook flags.
* Shares use only **one selected cookie**, while comments use **all cookies randomly**.
* The tool will always show a **live progress count** and a final summary.

> [!NOTE]
> - If you encounter any issues or difficulties, don't hesitate to reach out and ask for assistance here. I’m here to help you with any problems you may face.
> - 
