# Command Page

This page is a quick command reference for the TerraLink project workspace.

## 1. Open the project folder

```bash
cd "c:/Users/ELCOT/TerraLink"
```

## 2. Check project contents

```bash
ls
```

```bash
dir
```

## 3. Git status and repository commands

```bash
git status
```

```bash
git add .
```

```bash
git commit -m "Your commit message"
```

```bash
git push origin main
```

```bash
git pull origin main
```

## 4. Create and switch branches

```bash
git checkout -b feature/your-name
```

```bash
git checkout main
```

```bash
git branch
```

## 5. View recent commit history

```bash
git log --oneline --decorate --graph --all
```

## 6. Arduino demo sketch commands

The active sketch is in [code/demo_led_blinking.cpp](code/demo_led_blinking.cpp). Use the Arduino IDE or Arduino CLI to compile and upload it.

### Open file in Arduino IDE

```bash
code "c:/Users/ELCOT/TerraLink/code/demo_led_blinking.cpp"
```

### If using Arduino CLI

```bash
arduino-cli compile --fqbn esp32:esp32:esp32 "c:/Users/ELCOT/TerraLink/code/demo_led_blinking.cpp"
```

```bash
arduino-cli upload -p COM3 --fqbn esp32:esp32:esp32 "c:/Users/ELCOT/TerraLink/code/demo_led_blinking.cpp"
```

> Replace `COM3` with the actual port of your board if needed.

## 7. Useful backup commands

```bash
git stash
```

```bash
git stash pop
```

```bash
git reset --hard HEAD
```

## 8. Quick project workflow

```bash
cd "c:/Users/ELCOT/TerraLink"
git status
git add .
git commit -m "Update project files"
git push origin main
```

## 9. Notes

- Use meaningful commit messages.
- Keep the project folder organized.
- Save all team progress before major changes.
- Use the Arduino sketch file as the main hardware demonstration reference.
