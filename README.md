# neovim
my Neovim  c++ and typescript lsp fish powershell Gruvbox

brew install --HEAD tree-sitter luajit neovim

git clone https://github.com/NavigationHazard/neovim.git 


npm install -g typescript typescript-language-server


run nvim in terminal

Inside nvim run:

  :PlugInstall 
  


npm install -g diagnostic-languageserver

npm i -g eslint_d prettier

Inside nvim again:

  :TSInstall javascript
  :LspInstall ccls 
  :LspInstall clang
