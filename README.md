## BDD + Capybara + PageObjects
Automação do site do Quinto Andar

### Instalando Ambiente no Mac

```ruby
1. Instalar o Homebrew:
   /usr/bin/ruby -e "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/master/install)"r
   
2. Instalando e configurando o rbenv:
   brew install rbenv
   echo 'eval "$(rbenv init -)"' >> ~/.bash_profile
   rbenv install -l
   rbenv install 2.6.0 #Ou versão superior estável
   rbenv local 2.6.0
   
3. Baixar ChromeDriver
   http://chromedriver.chromium.org/
```

### Instalando Gerenciador de gems do Ruby

```ruby
gem install bundler
```

### Executando o Projeto :dart:

```ruby
1. Faça um clone do projeto:
   git clone https://github.com/Thialison/basic-web-automation.git

2. Acesse a pasta pelo terminal e execute o comando:
   bundle install

3. Executando cenário de busca de apartamento:
   cucumber

```
