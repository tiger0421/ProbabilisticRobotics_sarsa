# ProbabilisticRobotics_sarsa
World: 4x4のグリッド
  
繰り返し回数: 1000

- 進行方向(8種類)：
1. ↑
2. ↓
3. ←
4. →
5. ↗
6. ↘
7. ↙
8. ↖

####落とし穴の実装
class State内
'''
def generate_hole(self, actions):
    for a in actions:
        self.Q[a] = 10000
'''

### 参考
https://github.com/ryuichiueda/probrobo2017/blob/master/09.ipynb

##Lisence
GNU GPL
