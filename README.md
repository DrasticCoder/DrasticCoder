#  Hello, World! 🌍<br> I'm Deep - aka [DrasticCoder] 👋 

 I'm here to blend code with a sprinkle of fun. Here’s a bit about me:
```typescript
type Mood = 'excited' | 'chilled' | 'tired';

interface WorkLifeBalance {
  task: string;
  mood?: Mood;
}

const funEmojis: Record<Mood, string> = {
  excited: '🚀',
  chilled: '😎',
  tired: '😴'
};

const professionalAdvice: Record<Mood, string> = {
  excited: "Awesome! Keep that energy going but stay sharp.",
  chilled: "Nice! Remember to keep the momentum going.",
  tired: "Take a break, recharge, and come back with fresh eyes."
};

function workLifeBalance({ task, mood = 'chilled' }: WorkLifeBalance): string {
  if (!funEmojis[mood]) {
    return "Oops! I think there's a mood typo. Try 'excited', 'chilled', or 'tired'.";
  }

  return `Task at hand: ${task} ${funEmojis[mood]}.\nAdvice: ${professionalAdvice[mood]}`;
}

// Example usage
const message = workLifeBalance({ task: "Refactor my latest web project", mood: "excited" });
console.log(message);
```
## About Me
🎯 **Coding Enthusiast:** I write clean code when the stars align. Otherwise, embrace the chaos.

♟️ **Chess Lover:** If my code is messy, at least my chess game is strategic.

🌐 **Web Developer:** Check out my work and about 'me' at [drasticcoder.in](https://www.drasticcoder.in/).

### Fun Fact
If I’m not at the keyboard, I’m probably analyzing my chess game or plotting my next coding project.

## Let’s Connect
Feel free to reach out if you share similar interests or just want to chat about code or [chess](https://www.chess.com/member/drasticcoder)!

[![LinkedIn](./img/linkedin.svg)](https://www.linkedin.com/in/deep-bansode/)
&nbsp;&nbsp;
[![Twitter](./img/twitter.svg)](https://twitter.com/drasticcoder)
&nbsp;&nbsp;
[![Mail](./img/gmail.svg)](mailto:codebydrastic@gmail.com)



<div align="right">

![Github Profile Views](https://komarev.com/ghpvc/?username=drasticcoder&color=181717&style=flat-square&label=Profile+Views)

</div>
