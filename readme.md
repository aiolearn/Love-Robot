<h1 align="center">Welcome to Love Robot 👋</h1>

# Love Robot

In the Love Robot project, we have written a Python program that automatically types the word 'Love' 10 times or more.

## Modules

We used the pyautogui module to do this project.

```python
import pyautogui as robot
```

## Usage

```python
for x in range(1, 100):
    # Stop for 0.3 seconds
    robot.sleep(0.3)
    
    # Simulation of typing the text "I love you..." with a specified time interval of 0.05 seconds
    robot.write('i love you...', interval=0.05)
    
    # Keystroke simulation 'Enter'
    robot.press('enter')
```

In the code below, we first define a loop, inside the loop we instruct the robot to run after 3 seconds and write "I love you" every half second and press enter once for each word it writes.

## Result

This project was written by Majid Tajanjari and the Aiolearn team, and we need your support!❤️

# ربات عاشق

در پروژه ربات عشق، ما یک برنامه پایتون نوشته ایم که به طور خودکار کلمه "Love" را 10 بار یا بیشتر تایپ می کند.

## ماژول ها

ما از ماژول pyautogui برای انجام این پروژه استفاده کردیم.

```python
import pyautogui as robot
```

## Usage

```python
for x in range(1, 100):
    # Stop for 0.3 seconds
    robot.sleep(0.3)
    
    # Simulation of typing the text "I love you..." with a specified time interval of 0.05 seconds
    robot.write('i love you...', interval=0.05)
    
    # Keystroke simulation 'Enter'
    robot.press('enter')
```

در کد زیر ابتدا یک حلقه تعریف می کنیم، داخل حلقه به ربات دستور می دهیم که بعد از 3 ثانیه اجرا شود و هر نیم ثانیه یکبار بنویسد "I love you" و برای هر کلمه ای که می نویسد یک بار اینتر را فشار دهید.

## Result

این پروژه توسط مجید تجن جاری و تیم Aiolearn نوشته شده است و ما به حمایت شما نیازمندیم!❤️