# 2019 fintech course hw0
- 我修改了助教 final_demo/modules 裡面的function get_coshow():
  原先助教採用前詞+後詞成為一個新詞，但這樣會有很多贅字。於是我依照
  domain how判斷，將形容詞副詞等可能出現在前頭的詞性擺前頭,放在pre_pos的list裡。
  而名詞等則放在post_pos.而前後字的詞性要分別在這兩個list，我才將其組合成一句新句。
  期望能較有意義。




