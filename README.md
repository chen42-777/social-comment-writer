# Social Comment Writer｜社群留言靈感庫

為 Instagram 與 Threads 貼文設計的 Codex skill。丟進截圖、貼文文案或情境描述後，它會生成自然、有梗、可直接複製的台灣繁中留言。

## 適合什麼情境

- 看完 IG／Threads 貼文，一時想不到怎麼留言
- 想要有梗、簡單直接、暖心或嘴但不惡意的回覆
- 想讓留言少一點標點，偶爾搭配剛好的 emoji
- 貼文適合時，想自然帶到活動或報名連結

## 產出原則

- 預設提供 6 則不同風格的短留言
- 使用自然的台灣繁體中文，不寫成生硬廣告文
- 每則回應會盡量對應貼文中的具體畫面、情境或笑點
- 標點保持精簡；emoji 會適量使用，不會每句都塞
- 支援「有梗幽默、簡單暴力、暖心、嘴但不惡意」等方向
- 若提供活動連結，最多只在 2 則適合的留言中原樣附上，不強行置入

## 使用方式

安裝此 skill 後，在 Codex 對話中直接描述需求，並附上貼文截圖或貼文內容即可。

```
幫我替這張 IG 截圖寫 6 則有梗留言
少一點標點 偶爾加 emoji
```

也可以指定風格：

```
幫我寫 5 則簡單暴力的 Threads 回覆
```

若要自然宣傳活動：

```
幫我替這篇貼文寫 6 則留言
活動連結是 https://example.com
只有適合的留言才幫我帶到
```

## 呼叫方式

```
Use $social-comment-writer to create natural Taiwanese Traditional Chinese replies for this social post.
```

## 注意事項

請只對你有權使用的截圖與貼文內容生成留言。此 skill 會避開仇恨、騷擾、歧視、冒充與針對私人身分的攻擊。

## 檔案結構

```
social-comment-writer/
├── SKILL.md
└── agents/
    └── openai.yaml
```
