  <img src="https://giffiles.alphacoders.com/111/111890.gif" width=1000px height=500px>
 
- 👋 I'm Khalil! (don't mispronounce it 😤)
- 🌱 I’m currently learning web development 
- 💞️ I’m looking to collaborate on anything that improves my coding skills 🚩
- 🗿  Top tier procrastination material: games + anime 🔥
- 🗽  I wanna leave my country (badly)
- 💢 Fluent in english! 

```python

 def main():
    class Life:
        def __init__(self, name, age, location):
            self.game_difficulty = 0
            self.name = name
            self.age = age
            self.location = location

        def evaluate_spawnPoint(self, spawnPoint):
            if "Brasil" in spawnPoint:
                self.game_difficulty += 100

        def evaluate_age(self, age):
            if age >= 18:
                self.game_difficulty += 20
            else:
                self.game_difficulty -= 20

        def name_check(self):
            answer = input("Is your name ordinary?").strip()
            if answer.lower() == "yes":
                self.game_difficulty -=10
            else:
                self.game_difficulty += 15

        def wealth_check(self):
            answer = input("Are you or your family rich?").strip()
            if answer.lower() == "yes":
                self.game_difficulty -= 10000000
            else:
                pass

        def uneventfulLifeCheck(self, *args):
            despairArray = [*args]

            if len(despairArray) >= 2:
                self.game_difficulty += 7
            else: 
                pass

    # very inefficient (for demonstration purposes) :smirk:
    instance = Life("Khalil Bohner", 16, "Chapeco - Santa Catarina - Brasil")
    instance.wealth_check()
    instance.name_check()
    instance.evaluate_age(instance.age)
    instance.evaluate_spawnPoint(instance.location)
    instance.uneventfulLifeCheck("https://store.steampowered.com", "https://www.crunchyroll.com")
    print(instance.game_difficulty)

if __name__ == "__main__":
    main()

```
guess i'm playing on 102 😥

Also, my last name is a pun.. bohner..
  <div>
  <img src="https://c.tenor.com/hz2ra-yKSR0AAAAd/like-it-says-in-the-book-blessed-and-cursed.gif" width=250px>
  </div>
  
<hr>

![Maymisk's GitHub stats](https://github-readme-stats.vercel.app/api?username=Maymisk&hide=contribs,prs&show_icons=true&theme=midnight-purple)




