# Phoneme tables

The phoneme system using here is a modified version of the VINA system, which was based on Anh Duy's system for Vietnamese VCV.

## Vowel nuclei

| Phoneme | IPA | Written representation | Example       | Phonetic        |
| ------- | --- | ---------------------- | ------------- | --------------- |
| a       | a   | a                      | c**à** chua   | [k a ch ua]     |
| ae      | ă   | ă, a                   | s**a**y mê    | [s ae Y m E]    |
| i       | i   | i, y                   | b**í** đao    | [b i d a W]     |
| u       | u   | u                      | c**ủ** sắn    | [k u s ae N]    |
| U       | ɨ   | ư                      | đơn c**ử**    | [d oe N k U]    |
| e       | ɛ   | e                      | n**é** tránh  | [n e ch a NH]   |
| E       | e   | ê                      | k**ể** chuyện | [k E ch w ia N] |
| oe      | ə   | ơ                      | giấc m**ơ**   | [z A K m oe]    |
| A       | ə̆   | â                      | t**â**n thời  | [t A N th oe Y] |
| o       | ɔ   | o                      | nh**ỏ** xíu   | [nh o s i w]    |
| O       | o   | ô                      | c**ô** gái    | [k O g a Y]     |
| ia      | iə̯  | ia, iê                 | kiến tạo      | [k ia N t a w]  |
| ua      | uə̯  | ua, uô                 | muôn vật      | [m ua N v A T]  |
| Ua      | ɨə̯  | ưa, ươ                 | lươn lẹo      | [l Ua N l e w]  |

There would have been [3] /ə̆/ for the last 3 diphthongs (the idea was to seperate the ə̆), but labeling it was too hard, so instead, I settled for adding 3 more vowels.

Rules:

- Vowels with a hat: uppercase version of the letter without the hat. E.g.: "â" is "a" with a hat, so the phoneme for "â" is [A].
- Only /ă/ and /ə/ couldn't neatly be represented by one letter, so I had to settled for diagraphs. [e] was chosen because any other vowels would result in them being misread as a dipthongs.

## Final consonants

| Phoneme | IPA     | Written representation | Example        | Phonetic          |
| ------- | ------- | ---------------------- | -------------- | ----------------- |
| Y       | j       | i, y                   | ma**y** mắn    | [m ae Y m ae N]   |
| W       | w       | o, u                   | ca**o** cả     | [k a W k a]       |
| M       | m       | m                      | â**m** thanh   | [A M th ae NH]    |
| N       | n       | n                      | ghe**n** tuông | [g e N t ua NG]   |
| NH      | ɲ~jŋ̟    | nh                     | gá**nh** nặng  | [g a NH n ae NG]  |
| NG      | ŋ       | ng                     | tan trườ**ng** | [t a N ch Ua NG]  |
| NGM     | ŋ͡m      | ng                     | cu**ng** kính  | [k u NGM k i NH]  |
| P       | p̚       | p                      | á**p** lực     | [a P l U K]       |
| T       | t̚       | t                      | má**t** mẻ     | [m a T m e]       |
| K       | k̚       | c                      | tạm gá**c**    | [t a M g a K]     |
| KP      | k͡p̚      | c                      | ngoạn mụ**c**  | [ng w a N m u KP] |
| CH      | c̚~jk̟̚    | ch                     | hữu í**ch**    | [h U W i CH]      |

[NGM] and [KP] is there due to /k, ŋ/ are articulated differently after /u, o, ɔ/, and I don't want to leave it up to context.

I could reduce [NH] and [CH] to [Y NG] and [Y K], but they have different articulations between speakers, and labeling the [Y] would be very difficult.

The reason for differentiating between initial consonants and final consonants can be illustrated by [k a y a nh A y]. Is it "cái anh ấy", or "cá da nhầy", or "cái a nhây"? That's why by differentating them, and rewrite the example to [k a Y a NH A Y], it'd be easier to determine that it's "cái anh ấy".

Rules:

- All final consonants are uppercase version of their initial consonants.
- /uk/ → [u KP], /uŋ/ → [u NGM]
- /ɔk/ → [o KP], /ɔŋ/ → [o NGM]
- /ok/ → [O KP], /oŋ/ → [O NGM]

## Initial Consonants

| Phoneme | IPA | Written representation | Example         | Phonetic            |
| ------- | --- | ---------------------- | --------------- | ------------------- |
| b       | ɓ   | b                      | mua **b**án     | [m ua b a N]        |
| d       | ɗ   | đ                      | **đ**i lại      | [d i l a Y]         |
| f       | f   | ph                     | trái **ph**ải   | [ch a Y f a Y]      |
| g       | ɣ   | g, gh                  | **g**õ cửa      | [g o k Ua]          |
| h       | h   | h                      | **h**ạnh phúc   | [h ae NH f u KP]    |
| k       | k   | c, k                   | **k**ỉ niệm     | [k i n ia M]        |
| kh      | x   | kh                     | trống **kh**ông | [ch O NGM kh O NGM] |
| l       | l   | l                      | **l**au chùi    | [l ae W ch u Y]     |
| m       | m   | m                      | cha **m**ẹ      | [ch a m e]          |
| n       | n   | n                      | **n**ắm tay     | [n ae M t ae Y]     |
| nh      | ɲ   | nh                     | cùng **nh**au   | [k u NGM nh ae W]   |
| ng      | ŋ   | ng                     | **ng**ôn tình   | [ng O N t i NH]     |
| s       | s   | s                      | chia **s**ẻ     | [ch ia s e]         |
| t       | t   | t                      | **t**ổng đài    | [t O NGM d a Y]     |
| th      | tʰ  | th                     | thề ước         | [th E Ua K]         |
| ch      | t͡ɕ  | ch                     | **ch**ung tay   | [ch u NGM t ae Y]   |
| v       | v   | v                      | **v**ây quanh   | [v A Y k w ae NH]   |
| z       | z   | d, gi, r               | **gi**ẻ lau     | [z e l ae W]        |
| w       | w   | (q)u, (th)o            | khô th**o**áng  | [kh O th w a NG]    |

## Southern Exclusives

| Phoneme | IPA   | Written representation | Example       | Phonetic        |
| ------- | ----- | ---------------------- | ------------- | ----------------|
| ck      | c     | ch                     | **ch**e đậy   | [ck e d A Y]    |
| y       | j     | d                      | **d**ành cho  | [y ae N ck o]   |
| w       | w     | qu                     | hào **qu**ang | [h a W w a NG]  |
| tr      | ʈ͡ʂ~ʈ  | tr                     | **tr**ẻ đẹp   | [tr e d e P]    |
| sh      | ʂ     | s                      | **s**âm banh  | [sh A M b ae N] |
| r       | ʐ, r  | r                      | cà **r**em    | [k a r e M]     |
| NM      | ŋ͡m    | n                      | tồ**n** tại   | [t O NM t a Y]  |
| TP      | k͡p̚    | t                      | tố**t** tánh  | [t O TP t ae N] |

 The purpose of the last two phonemes can be easily illustrated by "đồn công an" [d O NM k O NGM a NG] and "phát lộc tốt lành" [f a K l O KP t O TP l ae N].

## Special

| Phoneme | IPA | Written representation | Example | Phonetic | Note         |
| ------- | --- | ---------------------- | ------- | -------- | ------------ |
| q       | ʔ   |                        |         |          | Glottal stop |
| vf      | ◌̰   |                        |         |          | Vocal fry    |
| mm      | m̩   |                        |         |          | Syllabic m   |
| nn      | n̩   |                        |         |          | Syllabic n   |
