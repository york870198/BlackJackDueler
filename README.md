# BlackJackDueler
https://york870198.github.io/BlackJackDueler/

這是一個實驗性的專案，用來測試 React 的功能。

## 此專案使用的工具
- [React](https://zh-hant.reactjs.org)
- [styled-components](https://styled-components.com)
- [webpack](https://webpack.js.org)

## 規則
回合起始時雙方各抽一張暗牌與一張明牌。

雙方不知道彼此的暗牌，由明牌數值較低的一方先進行他的行動。

每當輪到一名玩家行動時，他可以選擇抽牌或是開牌。

如果選擇抽牌，則檢查是否爆牌（點數合計超過 21），爆牌則立刻落敗，否則換另一名玩家行動。

如果選擇開牌，則雙方打開手中的牌比較點數大小，較高的一方獲勝。

## 你也許會想問的問題

### 這跟正常的 21 點規則不太一樣
對，一般的玩法是所有玩家都可以自由要牌直到想停止，而這裡不是。

這是因為這個機制是以「作為 RPG 遊戲中的回合制對戰」的前提設計的，

我會在空閒的時候繼續擴充它，加入生命值、技能等要素。
  
### 程式碼有點紊亂
豈止有點。

就如最上面寫著的，這是實驗性的，老實說我過程中就是想到什麼才寫什麼。

對於該如何重構我姑且有簡單的構想，等我有時間時我會試著把它修改到至少我自己看的順眼。

### 這東西花了多少時間
三天，扣掉我逃避現實跑去打電動的時間大概十來個小時。
