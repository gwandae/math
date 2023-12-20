
# Line head conversion
# Note: this rule can't apply to the very first line of the document
'\n》|' -> '\n>|'
'\n、|' -> '\n/|'


# CN symbols to EN
'。。|' -> '.|'
'》》|' -> '>|'
'、、|' -> '/|'
'；；|' -> ';|'
'，，|' -> ',|'

# Auto-pair, Input Conversion, and Deletion
'《《|》' -> '<|' # this one take higer priority than the next line
'《|'    -> '《|》'
'《|》'   -x '|'
'（（|）' -> '(|)'
'（|'     -> '（|）'
'（|）'   -x '|'

# Auto code block
'··|'  -> '`|`' # inline block
'`·|`' -> '```|\n```'

# have fun converting!
'dpx|' -> 'don\'t panic|'
'\df|' -> '\dfrac{|'
'\lim|' -> '\displaystyle\lim_{|'
'\sum|' -> '\displaystyle\sum_{|'
'\int|' -> '\displaystyle\int|'
'\ba|' -> '$\begin{aligned}\n|\n\end{aligned}$'
'\lf|' -> '\left(|'
'\rt|' -> '\right)|'
'\bb|' -> '$\begin{align*}\n|\n\end{align*}$'
'&*|' -> '\\&=|'
'\#|' -> '#### |'
'\bc|' -> '\begin{cases}|\end{cases}$'
'iii)|' -> '\text{iii) }|'
'ii)|' -> '\text{ii) }|'
'i)|' -> '\text{i) }|'
'\bs|' -> '\because|'
'\th|' -> '\therefore|'
'\tl|' -> '\text{Let\quad }|'
'\il|' -> '\text{일 때, }|'
'\=|' -> '\\&=|'
'\sp|' -> '**<span style="color: red;">$\qquad$답: $|$</span>**'
'\rb|' -> '\rbrace|'
'\lb|' -> '\lbrace |'
'\rv|' -> '\rvert|'
'\lv|' -> '\lvert |'
'\cc|' -> '\cancel|'
'\ct|' -> '\cancelto{|}{'
'\1|' -> '***문제|.***\n\n\n\n$\quad ①\, \n\quad ②\, \n\quad ③\, \n\quad ④\, \n\quad ⑤\, \n$ \n<details> \n  <summary>상세한 풀이</summary> \n   <p><img src="/assets/.png"/></p>\n </details>\n\n***\n\n' 
'\im|' -> '<img src="/assets/|"/>'
'\dx|' -> '\dfrac{d}{dx}|'
'\2|' -> '***단답형|.***\n\n\n\n<details> \n  <summary>상세한 풀이</summary> \n   <p><img src="/assets/.png"/></p>\n</details>\n\n***\n\n'
'\3|' -> '***서술형|.***\n\n\n\n<details> \n  <summary>상세한 풀이</summary> \n   <p><img src="/assets/.png"/></p>\n</details>\n\n***\n\n'


# Selection Insert Rules
'·'  -> '`' + '`'
'￥'  -> '$' + '$'
'《'  -> '《' + '》'
'<'  -> '<' + '>'
