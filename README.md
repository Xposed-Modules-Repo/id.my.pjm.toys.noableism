# NoAbleism

## About this module / 關於該模組

Enforce package visibility for accessibility service discovery APIs. Supports Android 9–16.

對無障礙服務探索API強制執行應用可見性原則。支持Android 9~16。

## FAQ

Q: Why does this module not work? I still get my accessibility services detected by such-and-such app!

A: This module's *only* job is to **enforce package visibility policies** for accessibility service discovery API surfaces. Modifying the applied visibility policy is entirely a different thing altogether. You need to have that set up by yourself.


Q: 為什麼這個模組不起作用？我的無障礙服務還是被某某應用程式偵測到了！

A: 本模組的*唯一*作用是對無障礙服務探索 API 介面**強制執行應用可見性原則**。修改所套用的可見性原則完全是另一回事。您需要自行完成相關設定。




Q: How do I go about doing that?

A: You may use [Hide My Applist](https://github.com/Dr-TSNG/Hide-My-Applist) for that, and ensure that the app you target cannot see apps that provide accessibility services you are trying to hide from the target.


Q: 我該怎麼做？

A: 您可以使用[隱藏應用列表](https://github.com/Dr-TSNG/Hide-My-Applist)來實現這一點，並確保您的目標應用程式無法看見那些提供無障礙服務（即您試圖對該目標隱藏的服務）的應用程式。
