<h2 align="center">
  Hi 👋! Welcome to my profile
</h2>

```rb
my_self = {
    name: "Deo Subarno",
    nickname: "Kochan",
    pronouns: "He/Him",
    skills: ["C#", "Java", "Ruby", "JavaScript", "Docker", "MySQL"],
    role: "Software Developer",
    say_hello: -> () { "Hello, my name is #{my_self[:name]}. You can call me #{my_self[:nickname]}" }
}

puts my_self[:say_hello].call
```
