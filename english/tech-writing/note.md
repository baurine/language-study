# Tech Writing

## 资源

- [Google Technical Writing Courses](https://developers.google.com/tech-writing)
- [免费学习资源推荐 | Google 面向工程师的技术写作课程](https://mp.weixin.qq.com/s/GmYhGczs5TQ222fqT1vCrg)
- [Google 技术写作](https://docs.google.com/document/d/16aoMrMGHPIR1i_eUNRvksdDdwcDG6KiOJN6Vfh-n8-s/edit)
- [Google 技术写作 (掘金转载)](https://juejin.im/post/5e7ad2f8e51d4526eb227be1)

工具：

- [剑桥词典](https://dictionary.cambridge.org/)
- [牛津词组搭配词典](http://www.freecollocation.com/)

  快速查询某个单词的常见搭配

- [Grammarly](https://app.grammarly.com/)
- [Capitalize My Title](https://capitalizemytitle.com/)

  英文文章的标题中，一般只有实词（动词、名词、形容词等）的首字母才需要大写，虚词（连词、介词等）不需要大写。但有时候，大于五个字母的虚词也需要大写首字母。

## Note 1

### Checklist

- 句子首字母大写
- 用句号隔开完整的两句话
- 不使用中文全角标点
- 英文标点后空一格
- And 的用法
- 使用连词连接相关联的句子
- 正确使用冠词 (a/an/the)
- 正确使用动词单复数
- 正确使用固定搭配

#### 句子首字母大写

英文句子的首字母要大写。

除专有名词以外，一般的句子里也只有首字母需要大写。

- 正确：For example, in MySQL, users can set `auto_increment_increment` and `auto_increment_offset` configuration...
- 错误：For example, In MySQL, users can set `auto_increment_increment` and `auto_increment_offset` configuration...

#### 用句号隔开完整的两句话

用句号隔开完整的两个句子。如果一定要用逗号，请在两句话之间使用正确的连词。

- 正确：We play badminton every Wednesday afternoon. It is a good opportunity to exercise.
- 错误：We play badminton every Wednesday afternoon, it is a good opportunity to exercise.

#### 不使用中文全角标点

对于中英文共有的标点符号，如逗号、句号、分号、冒号等，英文中应该使用半角的标点。

对于中文特有的标点符号，如书名号（《》）、顿号（、）等，应该根据实际情况替换为英文标点。

- 书名号 -> 斜体/引号
- 顿号 -> 逗号

例子：

- 正确：such as Bilibili, UCloud, TongCheng
- 错误：such as Bilibili、UCloud、TongCheng

#### 英文标点后空一格

- 正确：In addition to the above, I also need to do documentation.
- 错误：In addition to the above,I also need to do documentation.

#### And 的用法

使用 "and" 来连接三个或以上的并列项时，"and" 前要加逗号。

- 正确：an actor who is tall, dark, and handsome
- 错误：an actor who is tall, dark and handsome

#### 使用连词连接相关联的句子

常用连词有以下几种：

- and（并列关系）
- because/so（因果关系）
- though/but（转折关系）

例子：

- 正确：I work in Hangzhou, so we communicate with each other through IM tools.
- 错误：I work in Hangzhou, we communicate with each other through IM tools.

#### 正确使用冠词 (a/an/the)

可数名词的单数形式前，需要使用冠词。

- 正确：what kinds of bugs occur with the highest frequency
- 错误：what kinds of bugs occur with highest frequency

例外：

- 特殊职位，如 Queen of England
- 固定词组，如 go to school, play football, have breakfast

#### 正确使用动词单复数

- 正确：Our team is responsible for validating them.
- 错误：Our team are responsible for validating them.

#### 正确使用固定搭配

- 正确：UTF is dedicated to providing an easier way to develop and execute test cases.
- 错误：UTF dedicates to provide an easier way to develop and execute test cases.

## Note 2 - Technical Writing (Lecture One)

- General principles
  - Style and tone
  - Second person
  - Present tense
- Words
  - Define new or unfamiliar terms
  - Use terms consistently
  - Use abbreviations properly
  - Capitalization
  - Disambiguate pronouns

### General principles

#### Style and tone

Conversational, friendly, and respectful

不需要太正式，也不能太生活化，口语化。

避免使用 "Please"，"Let's do something"，而是需要更直接。

- Not good：For additional information about DM, **please** consult _Data Migration Overview_ in the TiDB documentation.
- Good: For additional information about DM, **consult** _Data Migration Overview_ in the TiDB documentation.
- Good: For additional information about DM, **see/refer to** _Data Migration Overview_.

#### Second person

Use second person rather than first person, ie, "you" instead of "we".

使用第二人称，或者避免使用主语。

#### Present tense

Use present tense rather than future tense (will/would)

- future tense: mild uncertainty as to how things unfold
- present tense: immediacy and demonstrates confidence

did --> have done sth

will do --> do

### Words

#### Define new or unfamiliar terms

link / glossary

#### Use terms consistently

#### Use acronyms properly

#### Capitalization

Trademarks, keywords, and other terms are always capitalized

- Capitalization in titles and headings
- Capitalization and colons
- Capitalization in glossaries

Capitalization in titles and headings

title/first heading:

- uppercase: notional words (n./v./pron./adj./adv.)
- lowercase: most form words (prep./art./conj.)
  - exceptions: between, without, alongside, underneath (>5 letters)
- uppercase: the first word
  - exceptions: some proper nouns

other heading: only the first word

- don't put a period at the end of a heading
- treat what follows the colon as a separate heading
  - example: `Step 1: Issue two sets of certificates for the TiDB clsuter`

#### Disambiguate pronouns

- personal pronouns: you, it, they (plus their objective and possessive forms)
- relative pronouns: which, that, who/whom/whose
- demonstrative pronouns: this, that, these, those

## Note 3 - Technical Writing (Lecture Two)

- Sentences
  - Clear sentences
  - Short sentences
  - Punctuation

### Short sentences

- Focus each sentence on a single idea
- Convert some long sentences to lists
- Reduce subordinate clauses (减少从句的使用)
- Distinguish `that` from `which`
- Eliminate or reduce extraneous words

#### Distinguish `that` from `which`

TiDB supports optimizer hints, **which** are based on the comment-like syntax introduced in MySQL 5.7.

Prepare a deployment machine **that** meets the following requirements: ...

If you read a sentence aloud and hear a pause just before the subordinate clause, then use which.

If you don't hear a pause, use that.

#### Eliminate or reduce extraneous words

- currently/now/already
- in fact/actually
- very/completely (disables..)/mainly/basically/really
- there be
- whether or not --> whether
- be able to --> can

Unnecessary verb + noun --> (strong) verb

- Not good: This document **provides a detailed description of** these key metrics.
- Good: This document **details** these key metrics.
- Not good: ...you can **make an estimate of** a larger number according to the number of Regions and Stores in the cluster.
- Good: ...you can **estimate** a larger number according to the number of Regions and Stores in the cluster.

总的来说，就是要简洁干脆，直接，不要碎碎叨叨，绕来绕去。

### Clear sentences

- Choose strong verbs
- Prefer active voice to passive voice (更倾向用主动语态)
- Reduce use of "there is/there are" (减少 there be 句型的使用)
- Mention the circumstance before providing the instruction
- Wary of certain kinds of contractions

#### Choose strong verbs

- Not good: If the upstream relay log is purged, an error **occurs**.
- Good: Purging the upstream relay log **triggers** an error.

#### Prefer active voice to passive voice

- Not good: BR is recommended **to be** deployed on the PD node.
- Good: It is recommended that **you deploy BR** on the PD node.

exceptions:

- To emphasize an object over an action.

  `The file is saved.`

- Readers don’t need to know who’s responsible for the action.

#### Mention the circumstance before the instruction

描述指令/行为之前，先说明目标。

- Not good: Refer to Data Migration Overview for additional information about DM.
- Good: For additional information about DM, refer to Data Migration Overview.
- Not good: Use the `DROP USER` statement to remove a user account: ...
- Good: To remove a user account, use the `DROP USER` statement: ...

#### Wary of certain kinds of contractions

- isn't --> is not
- don't --> do not
- can't --> cannot
- you’re --> you are

### Punctuation

- Backticks (`)
- Commas (,)
- Semicolons (;)
- Parentheses ({})
- Slashes (/)
