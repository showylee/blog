---
title: $vim vimconf2019record.md
date: "2019-11-04"
category: Conference
tags: 
    - conference
cover: ./vim_log.png
---

# 概要
Vimの国際カンファレンス、VimConf2019に参加しました。VimConfへの参加は今回が初めてです。  
どれもこれも話の内容が高度で知見！という感じでした（雑な感想）。  
多くの熱いVimmerたちの熱い講演を丸一日堪能できる最高のイベントで、mattnさんやShougoさんなどVimを使っていたらお世話にならないことはないBigVimmerの方々も参加されています。  
僕はなんとなくターミナルからファイル開く時はVimって感じでVimを使っているライトユーザーでしたが、今回の参加でもっとVim使いこなしたい、Vimのコミュニティに貢献できるようになりたいというモチベーションの高まりが起こりました。  
以下、基調講演の大雑把な要約と感想です。ただ、同時翻訳を聞いてなんとか理解している部分も多いので間違いがあるかもしれません。  

# keynote
いきなり英語でハードル高い。  
昨年はVimの作者であるBram氏を招いたそうですが、今年の講演も大変豪華で、vim-lspの開発者やNeovimのメンテナーによる講演でした。  
まずはvim-lspの開発者Prabir氏の講演。lspの開発経緯について。  
色々なエディタを触ってきた（それは自分の選択だったり、会社に選択させられたり）が、新しいエディタを触るたび、新しいキーコンフィグを覚えるまで生産的に仕事が出来ない。  
仕事と私生活でエディタを統一したい。言語ごとにプラグインを入れて、依存する言語をそれぞれで管理するのは、特にWindowsでは大変だった。  
それがvim-lspの開発につながる。  
また、古くからあるVimの歴史について、Vimは今ルネサンス期で、再び盛り上がりを見せている。  
そして今後VimはどうRevolutionしていくのか。  
Vimに出来ること、何が可能で何が不可能ということはない。全てはトライすれば可能だ、という言葉が印象的でした。  
難度の高い内容の話が同時翻訳と合わせて2つの言語で流れ込んでくるので、この講演だけで凄く疲れました。  
2つ目の基調講演はneovimのメンテナーJustin氏の講演。  
Editorの歴史やNeovimの開発経緯、そしてNeovimの機能概要やLuaの話。  
Luaは時間が足りず、話しきれなかったみたいで残念でした。  
NeovimはVimからユーザーを食うために開発されたわけではなく、より多くの競合がある状態が健全であるという考え。  
Vimは好きだけど、Vimの開発スピードは遅く、もっと良くできるのにと思っているユーザー達の選択肢になるため、頻繁にアップデートするVimを目指した。  
事実、1度だけ4日間Commitがなかっただけで、"Is Neovim Dead?"という記事が出るほど、開発に熱量があった。  
また、NeovimがForkされた後から、Vimもどんどん開発スピードが上がり始めた。  
なぜフルスクラッチでエディタを作らず、VimをForkしたかについては、むしろ何故Forkしないのか、これまでVimが考え、積み上げてきた難しい考慮事項に、我々が再び頭を悩ませる必要がなくなるのに。と言っていたのが目から鱗でした。  

# Session
午後からはSpeakersのSessionでした。Vimmerの方々がVimPluginやVimそのものの機能、Vimコミュニティへの貢献、Vimを使った働き方など、Vimに関連する多種多様なお話を聞くことができました。  
Sessionの後はLTもあり、こちらも非常に熱いお話が多かったです。  

# VimConfを終えて
自分も含め、20代や学生などの若い世代の参加者が多い印象でした。基調講演での”Vimの再盛”が実感できます。  
また、VimConfを通じて、Vimに関していくつか生まれた思いがあります。  
まずはなんとなくVimを使い、Vim自身のもつポテンシャルを理解しないうちにIDEのような機能欲しさになんでもかんでもPluginを入れ込んでしまっていたことへの反省。  
明日にはこれまでのVimrcを捨て、しばらくはVanillaVimを使い倒してみます。とりあえずは、Danishさんのお話にあったように、チームメンバーからお小言を言われないように気をつけながら。  
使い倒して、不便なところが出てきたらまずはキーコンフィグをカスタムするところからVimrcを整えていきます。  
また、これまではNeovimを使っていたのですが、基本に立ち返ってVimからやり直してみます。  
Vimをビルドして、テストを流して、少しずつContributeという視点も持ちながらVimを使います。  

ごちゃごちゃ書きましたが、一番大事なのはこのモチベーションを持続させることですね。本当に。  
:wq  
