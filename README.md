 - 👋 I'm Khalil
- 🌱 I’m currently learning web development 
- 💞️ I’m looking to collaborate on anything that improves my coding skills 🚩
- 🗽  I wanna leave my country (badly)
- 💢 Fluent in english! 

```typescript

 function main() {
   
    interface ILife {
      evaluateSpawnPoint(spawnPoint: string): void;
      evaluateAge(age: number): void;
      evaluateName(name: string): void;
      uneventfulLifeCheck(...args: string[]): void;
    }

    class Life implements ILife {
        game_difficulty = 0

        evaluateSpawnPoint(spawnPoint: string): void {
            if (spawnPoint.includes('Brasil')) {
                this.game_difficulty += 100
            }
        }

        evaluateAge(age: number): void {
            age >= 18 ? this.game_difficulty += 20 : this.game_difficulty -= 20
        }

        evaluateName(name: string): void {
            const answer = prompt("Is your name ordinary?")?.trim()

            if (answer?.toLowerCase() == "yes") {
                this.game_difficulty -=10
                return
            }

            this.game_difficulty += 15
        }

        uneventfulLifeCheck(...args: string[]): void {
            const nerdyHobbies = args

            if (nerdyHobbies.length >= 2 ) {
                this.game_difficulty += 7
            }
        }
    }
                
    const life = new Life()
    life.name_check('Khalil Bohner')
    life.evaluate_age(16)
    life.evaluate_spawnPoint("Chapeco - Santa Catarina - Brasil")
    life.uneventfulLifeCheck("https://store.steampowered.com", "https://www.crunchyroll.com")
    console.log(life.game_difficulty)
}

main()

```
difficulty: 102 😥

dont mind my last name
  
<hr>

![Maymisk's GitHub stats](https://github-readme-stats.vercel.app/api?username=Maymisk&hide=contribs,prs&show_icons=true&theme=midnight-purple)




