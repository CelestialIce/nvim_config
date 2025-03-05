### Prerequisites

Ensure you have the following installed:

- **Neovim** (v0.5+ recommended)  
  Install using:
  ```sh
  sudo apt install neovim   # Ubuntu/Debian
  brew install neovim       # macOS (Homebrew)
  yay -S neovim             # Arch Linux (yay)
  ```
- **Git**  
  ```sh
  sudo apt install git      # Ubuntu/Debian
  brew install git          # macOS (Homebrew)
  ```
- **Node.js & npm** (for LSP & plugins)  
  ```sh
  sudo apt install nodejs npm  # Ubuntu/Debian
  brew install node            # macOS (Homebrew)
  ```

### 📦 Installation Steps

1. **Clone this repository**  
   ```sh
   git clone https://github.com/CelestialIce/nvim_config.git ~/.config/nvim
   rm -rf ~/.config/nvim/.ssh
   ```

2. **Install dependencies**  
   Open Neovim and install plugins:
   ```sh
   nvim
   ```
   Then inside Neovim, run:
   ```
   :PackerSync
   ```

3. **Restart Neovim**  
   ```sh
   nvim
   ```

