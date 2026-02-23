# Run LLM Scripts in Emacs (No Packages)

# Create the scripts folder

mkdir ~/bin

# Add it to your PATH

~/.profile

export PATH="$HOME/bin:$PATH"

source ~/.profile

# Install the LLM tool

pip install llm

# Add your API key

llm keys set claude

# Create the "correct" script

See script in repo called "correct"

# Make it executable

chmod +x ~/bin/correct

# Use It in Emacs

1. Open Emacs
2. Type: "I realy enjoyd the consert last nite."
3. Highlight the text
4. Press `M-|` (Alt+Pipe)
5. Type: `correct`
6. Press Enter

## Part 5: Creating New Scripts (1 minute)

Once you understand the pattern, you can create any script you want. But you don't have to write them yourself.

Use Claude Code. Just ask:
- 'Create a script that summarizes text'
- 'Create a script that translates to Spanish'
- 'Create a script that explains concepts in simple terms'




