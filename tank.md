# 無敵

| TTS | RegularExpression | Category |
| --- | --- | --- |
| `${name}のウォーキングデッド` | `(?<name>\w*?)に「*?ウォーキングデッド」の効果。$` | `Tank` |
| `${name}のリビングデッド` | `(?<name>\w*?)の「リビングデッド」$` | `Tank` |
| `${name}のインビンシブル` | `(?<name>\w*?)の「インビンシブル」$` | `Tank` |
| `${name}のボーライド` | `(?<name>\w*?)の「ボーライド」$` | `Tank` |
| `${name}のホルムギャング` | `(?<name>\w*?)の「ホルムギャング」$` | `Tank` |

# 挑発

* ファミリーネームのみ（鯖名を読み上げない）

  * RegularExpression

    ```
    (?<name>[A-Z][a-z]*?)(|Aegis|Atomos|Carbuncle|Garuda|Gungnir|Kujata|Tonberry|Typhon|Alexander|Bahamut|Durandal|Fenrir|Ifrit|Ridill|Tiamat|Ultima|Anima|Asura|Chocobo|Hades|Ixion|Masamune|Pandaemonium|Titan|Belias|Mandragora|Ramuh|Shinryu|Unicorn|Valefor|Yojimbo|Zeromus)の「挑発」$
    ```

    * TTS

    ```${name}の挑発```

    * Category

    ```Tank```

* フルネーム（鯖名を読み上げない）

  * RegularExpression

    ```
    (?<name>[A-Z][a-z]*? [A-Z][a-z]*?)(|Aegis|Atomos|Carbuncle|Garuda|Gungnir|Kujata|Tonberry|Typhon|Alexander|Bahamut|Durandal|Fenrir|Ifrit|Ridill|Tiamat|Ultima|Anima|Asura|Chocobo|Hades|Ixion|Masamune|Pandaemonium|Titan|Belias|Mandragora|Ramuh|Shinryu|Unicorn|Valefor|Yojimbo|Zeromus)の「挑発」$
    ```

    * TTS

    ```${name}の挑発```

    * Category

    ```Tank```

* ファミリーネームのみ（鯖名を読み上げる）

| TTS | RegularExpression | Category |
| --- | --- | --- |
| `${name}の挑発` | `(?<name>\w*?)の「挑発」$` | `Tank` |

* フルネーム（鯖名を読み上げる）

| TTS | RegularExpression | Category |
| --- | --- | --- |
| `${name}の挑発` | `(?<name>\w*?)の「挑発」$` | `Tank` |

# シャーク

| TTS | RegularExpression | Category |
| --- | --- | --- |
| `${name}のシャーク` | `(?<name>\w*?)の「シャーク」$` | `Tank` |


<!-- 
(?<name>\w*\w*?)(|Aegis|Atomos|Carbuncle|Garuda|Gungnir|Kujata|Tonberry|Typhon|Alexander|Bahamut|Durandal|Fenrir|Ifrit|Ridill|Tiamat|Ultima|Anima|Asura|Chocobo|Hades|Ixion|Masamune|Pandaemonium|Titan|Belias|Mandragora|Ramuh|Shinryu|Unicorn|Valefor|Yojimbo|Zeromus)の「挑発」$ -->
