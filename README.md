# Installation

1. Install the latest version of starship.

   - With Shell.
  
    ```bash
    curl -sS https://starship.rs/install.sh | sh
    ```

   - With Homebrew.

    ```bash
    brew install starship
    ```

2. Add this line to the end of your .zshrc

    ```bash
    eval "$(starship init zsh)"
    ```

3. Clone this repository to your .config directory.

    ```bash
    git clone git@github.com:JoseFerAlvarez/starship.git
    ```

4. Add this line to your .zshrc

    ```bash
    export STARSHIP_CONFIG=~/.config/starship/starship.toml    
    ```
