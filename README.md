# Welcome to Agile Lab!

This is our technical test. Once you are done, you can either upload the answers to your own repository and share us the link, or you can zip your answers up and send it directly to us via email!

Enjoy!

## 1. Anagram Tester

An anagram is created by re-arranging the letters of a word. For example, the word `LISTEN` is an anagram of `SILENT`.
You can find the definition in [Wikipedia](https://en.wikipedia.org/wiki/Anagram).
Below is a skeleton defenition of a method for testing if two words make an anagram. Your task is to implement this
method, using Ruby. It should take in two strings and return `true` if the two words make an anagram, or `false` if it's not.

```ruby
def anagram?(first_word, second_word)
  # Add your implementation here
end
```

**Rules:**
 - You don't need to care about upper- and lowercase letters. That is, `A` and `a` can be considered the same for the purposes of this test.
 - You only need to care about single words. The method does not need to handle sentences.
 
 
## 2. Anonymous Chat

You are tasked to create a Anonymous Chat where public is able to initiate a anonymous conversation with the admin

You are to only required to create the `routes.rb` that can fulfil all the requirements listed below.

```ruby
# config/routes.rb
Rails.application.routes.draw do
  # Add your routes for Anonymous Chat
end
```

**Requirements:**
 - Public can initiate the chat
 - Admin can acknowledge that they have seen the chat (not messages).
 - Admin can response to the chat with the person who initiate the chat.
 - Admin can closed the conversation.
 - Admin cannot initiate the chat.


## 3. Bug Fixing

When client or users reported an issue to you, describe what you do next.
How do you go about trouble shooting the issue? Depending on what you find, what will your next step be? When do you
consider the issue fixed or resolved?

**Tips:**
- You are free to make **ANY** assumptions, write down your assumptions.

## 4. Taking over an old project

You have recently been assigned to an old project, the previous developer had already left and you are tasked to take over the project and implement new features.
However you are facing some problems, the new feature that you are implementating doesn't seem to go well with the existing features.
The more you code, the more edge case you encounter.

Describe, in as much detail as you like, how you would handle this situation.

**Tips:**
- You are free to make **ANY** assumptions, write down your assumptions.
