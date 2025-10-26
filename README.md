

# 🎨 PS1-bash-prompts

Beautiful and customizable **Bash PS1 prompts** with **real ANSI gradient backgrounds** behind text — no scripts, no dependencies, just pure Bash magic.

---

## ✨ Features

- True gradient backgrounds directly in your PS1  
- Works with any modern terminal (Kitty, Alacritty, GNOME Terminal, Konsole, etc.)  
- Clean minimalist design — *no Powerline or Starship required*  
- Easy setup: paste one line into `~/.bashrc`  
- Includes multiple color variants (Blue, Red, Green, Purple, Gold)

---

## 💡 How It Works

Each prompt uses **ANSI escape codes** to draw a background gradient under your username (`\u`) and optionally ends with a Powerline arrow (``) if your font supports Nerd Fonts.

Example visual layout:

▉▉▉▉ user 


---

## 🧩 Installation

### 1. Copy one of the prompt lines below  
Paste it at the bottom of your `~/.bashrc`.

### 2. Reload Bash  
```bash
source ~/.bashrc

✅ Done — no scripts, no sourcing other files.
🔷 Blue Horizon

Elegant deep-blue gradient behind username.

Preview:
(insert your screenshot here)

PS1="\[\e[48;5;18m\] \[\e[48;5;19m\]\u\[\e[48;5;20m\] \[\e[48;5;21m\] \[\e[0m\]\[\e[38;5;21m\]\[\e[0m\] "

🔴 Crimson Horizon

Warm red gradient — subtle yet strong.

Preview:
(insert your screenshot here)

PS1="\[\e[48;5;52m\] \[\e[48;5;88m\]\u\[\e[48;5;124m\] \[\e[48;5;160m\] \[\e[0m\]\[\e[38;5;160m\]\[\e[0m\] "

🟢 Emerald Wave

Calm green tones with natural transitions.

Preview:
(insert your screenshot here)

PS1="\[\e[48;5;22m\] \[\e[48;5;28m\]\u\[\e[48;5;34m\] \[\e[48;5;40m\] \[\e[0m\]\[\e[38;5;40m\]\[\e[0m\] "

🟣 Violet Storm

Royal purple gradient for dark themes.

Preview:
(insert your screenshot here)

PS1="\[\e[48;5;54m\] \[\e[48;5;55m\]\u\[\e[48;5;91m\] \[\e[48;5;93m\] \[\e[0m\]\[\e[38;5;93m\]\[\e[0m\] "

🟡 Golden Ember

Rich yellow-orange gradient with soft warmth.

Preview:
(insert your screenshot here)

PS1="\[\e[48;5;94m\] \[\e[48;5;130m\]\u\[\e[48;5;166m\] \[\e[48;5;220m\] \[\e[0m\]\[\e[38;5;220m\]\[\e[0m\] "

💠 Without Nerd Font

If your terminal doesn’t support Powerline symbols (), replace it with ◢ or any Unicode shape.

Example:

PS1="\[\e[48;5;18m\] \[\e[48;5;19m\]\u\[\e[48;5;20m\] \[\e[48;5;21m\] \[\e[0m\]\[\e[38;5;21m\]◢\[\e[0m\] "

⚙️ Customization

You can tweak:

    48;5;XX → background color (see ANSI 256 color chart

    )

    Symbol (, ▶, ◢, etc.)

    \u, \h, or \w → show username, host, or working directory

Try colors interactively:

echo -e "\e[48;5;27m  test  \e[0m"

🧠 License

MIT License — free to modify, reuse, and share.
Created with ❤️ for minimal Bash aesthetics.
📸 Coming Soon

    Screenshots for all variants

    Auto-fit gradient for dynamic username lengths

    Optional working directory or git branch segments

