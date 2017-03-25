---
layout: post
title:  "Data driven business (Spotify-2)"
date:   2017-03-24 14:38:20 +0900
tags: databusiness spotify discoverweekly
comments: true
---

Data driven business [Spotify-2]

Discover Weekly 출시된 이후 이 기능의 성공에 관한 많은 이야기들이 보도되었다. 흥미로웠던 건 Spotify도 자체적으로 분석 및 평가하여 공유한 내용인데, 이를 중심으로 이번 포스트를 채워보려고 한다.

# 목차
{:.no_toc}
*[ ]안의 내용은 출처*

* ToC
{:toc}

---

# [Spotify] 출시 배경

[What made Discover Weekly one of our most successful feature launches to date? By Sofie Lindblom, labs.spotify.com](https://labs.spotify.com/2015/11/18/what-made-discover-weekly-one-of-our-most-successful-feature-launches-to-date/)

매주 월요일 7,500백만개의 특별한 믹스테이스를 세상의 음악을 사랑하는 사람들에게 전달한다는 생각. 이 아이디어는어떻게 나오게 된 걸까?

2011년, Spotify는 크리스마스를 기념하여 사용자들에게 줄 선물을 생각했고, 이 아이디어는 마케팅 팀에 의해 'Year in Music(YiM)'로 발전된다.  이 기능은 일년 단위로 사용자가 주로 들었던 음악만을 플레이리스트로 제공했기 때문에, 기능이 확장되어 새로운 음악도 동시에 제공하는 'Play it forward'까지 변화하게 된다.  

그러나 이와 같은 아이디어 안에서 새로운 음악을 발견하는데는 사용자들의 많은 시간과 관심이 요구되어진다. YiM 기반의 아이디어는 미래의 발견에 적합하지 않았고, 치열한 논의를 거쳐 최종적으로 Discover Weekly의 첫 번째 버젼이 나오게 된다.

* Year in Music (2011) -> Play it forward(2014) -> Discover Weekly(2015)


> 아이디어부터 사용자가 원하는 어떤 것까지 가보자!

Spotify 팀은 반복적인 실험을 통해 플레이리스트의 가장 적절한 길이와 주기를 파악한다. 적은 수의 곡에 더 특별하게  느끼는 것을 알게 되었고, 이에 따라 길이는 2시간, 주기는 일주일에 한 번으로 최종 결정하게 된다.

이후 개발된 기능에 대해 테스트가 필요했는데, Spotify 직원들을 대상으로 하기엔 그들이 평범한 음악팬은 아니었기 때문에 무리가 있다고 판단하고. 결국, 실제 사용자에게 구글설문지를 이용하여 이 기능에 대한 의견을 물어 1,500명의 응답을 얻는다. 그리고 이 결과는 Discover Weekly의 믹스테이프가 훌륭하다는 확신을 주게 된다.

원문의 마지막 부분에는 What we learned라는 항목이 나오는데, 여기에 따로 작성하지는 않았지만, 내가 생각하기에는 가장 중요한 부분이 아닌가 싶다. 어떤 일 또는 프로젝트를 마친 뒤, 우리가 배운 부분에 대해서 회고하는 것은 다음 프로젝트를 진행하는 과정에서 큰 힘을 발휘할 것이다. 이를 알면서도 끝났다는 해방감 또는 다음 스케쥴에 쫒겨 자주 잊게 되는것 같다.

역시 Spotify는 이러한 세심한 부분까지 놓치지 않는구나.

---

# [Melmagazine & Quartz] 두 기자의 Discover Weekly 사용기

[How Spotify Solved for the ‘Paradox of Choice’ By John Mcdermott, Learn, melmagazine.com](https://melmagazine.com/how-spotify-solved-for-the-paradox-of-choice-28c4a2f0d09f#.nx4l7mitl)

[The magic that makes Spotify’s Discover Weekly playlists so damn good
By Adam Pasick, qz.com](https://qz.com/571007/the-magic-that-makes-spotifys-discover-weekly-playlists-so-damn-good/)

# [Spotify] 아이디어부터 개발까지

[From Idea to Execution: Spotify's Discover Weekly
By Chris Johnson, Engineering Manager, spotify.com](https://www.slideshare.net/MrChrisJohnson/from-idea-to-execution-spotifys-discover-weekly/20-2008_2012_2015Slide_from_Dan)

# [Paper] Discover Weekly에 적용된 추천 모델


[Koren, Y., Bell, R., & Volinsky, C. (2009). Matrix factorization techniques for recommender systems. Computer, 42(8).](https://datajobs.com/data-science-repo/Recommender-Systems-[Netflix].pdf)

[Mikolov, T., Sutskever, I., Chen, K., Corrado, G. S., & Dean, J. (2013). Distributed representations of words and phrases and their compositionality. In Advances in neural information processing systems (pp. 3111-3119).](http://papers.nips.cc/paper/5021-distributed-representations-of-words-and-phrases-and-their-compositionality.pdf)
