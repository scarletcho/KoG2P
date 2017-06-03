# KoG2P
한국어의 문자열로부터 발음열을 생성하는 파이썬 기반 G2P 패키지입니다.  
터미널에서 원하는 문자열을 함께 입력해 사용할 수 있습니다.

	$ python g2p.py '열 여덟째 사람'
</br>
## Requirements
- Python 2.7 or 3
</br>
## Symbol table
| C/V       | Position    | Symbols in Hangul | Symbols in KoG2P |
|-----------|-------------|-------|-------|
| consonant | onset       | ㅂ    | p0    |
| consonant | onset       | ㅍ    | ph    |
| consonant | onset       | ㅃ    | pp    |
| consonant | onset       | ㄷ    | t0    |
| consonant | onset       | ㅌ    | th    |
| consonant | onset       | ㄸ    | tt    |
| consonant | onset       | ㄱ    | k0    |
| consonant | onset       | ㅋ    | kh    |
| consonant | onset       | ㄲ    | kk    |
| consonant | onset       | ㅅ    | s0    |
| consonant | onset       | ㅆ    | ss    |
| consonant | onset       | ㅎ    | h0    |
| consonant | onset       | ㅈ    | c0    |
| consonant | onset       | ㅊ    | ch    |
| consonant | onset       | ㅉ    | cc    |
| consonant | onset       | ㅁ    | mm    |
| consonant | onset       | ㄴ    | nn    |
| consonant | onset       | ㄹ    | rr    |
| consonant | coda        | ㅂ    | pf    |
| consonant | coda        | ㅍ    | ph    |
| consonant | coda        | ㄷ    | tf    |
| consonant | coda        | ㅌ    | th    |
| consonant | coda        | ㄱ    | kf    |
| consonant | coda        | ㅋ    | kh    |
| consonant | coda        | ㄲ    | kk    |
| consonant | coda        | ㅅ    | s0    |
| consonant | coda        | ㅆ    | ss    |
| consonant | coda        | ㅎ    | h0    |
| consonant | coda        | ㅈ    | c0    |
| consonant | coda        | ㅊ    | ch    |
| consonant | coda        | ㅁ    | mf    |
| consonant | coda        | ㄴ    | nf    |
| consonant | coda        | ㅇ    | ng    |
| consonant | coda        | ㄹ    | ll    |
| consonant | coda        | ㄱㅅ  | ks    |
| consonant | coda        | ㄴㅈ  | nc    |
| consonant | coda        | ㄴㅎ  | nh    |
| consonant | coda        | ㄹㄱ  | lk    |
| consonant | coda        | ㄹㅁ  | lm    |
| consonant | coda        | ㄹㅂ  | lb    |
| consonant | coda        | ㄹㅅ  | ls    |
| consonant | coda        | ㄹㅌ  | lt    |
| consonant | coda        | ㄹㅍ  | lp    |
| consonant | coda        | ㄹㅎ  | lh    |
| consonant | coda        | ㅂㅅ  | ps    |
| vowel     | monophthong | ㅣ    | ii    |
| vowel     | monophthong | ㅔ    | ee    |
| vowel     | monophthong | ㅐ    | qq    |
| vowel     | monophthong | ㅏ    | aa    |
| vowel     | monophthong | ㅡ    | xx    |
| vowel     | monophthong | ㅓ    | vv    |
| vowel     | monophthong | ㅜ    | uu    |
| vowel     | monophthong | ㅗ    | oo    |
| vowel     | diphthong   | ㅖ    | ye    |
| vowel     | diphthong   | ㅒ    | yq    |
| vowel     | diphthong   | ㅑ    | ya    |
| vowel     | diphthong   | ㅕ    | yv    |
| vowel     | diphthong   | ㅠ    | yu    |
| vowel     | diphthong   | ㅛ    | yo    |
| vowel     | diphthong   | ㅟ    | wi    |
| vowel     | diphthong   | ㅚ    | wo    |
| vowel     | diphthong   | ㅙ    | wq    |
| vowel     | diphthong   | ㅞ    | we    |
| vowel     | diphthong   | ㅘ    | wa    |
| vowel     | diphthong   | ㅝ    | wv    |
| vowel     | diphthong   | ㅢ    | xi    |
  
NB. IPA symbols for Korean phones can be found in the following page: [IPA for Korean](https://en.wikipedia.org/wiki/Help:IPA_for_Korean).   
