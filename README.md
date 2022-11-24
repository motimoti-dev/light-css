# light-css
文字数をできるだけ抑えてCSSを書くための奴です。site speed insightsで高評価を貰うために作成されたものです。
使用頻度が高いものだけ定義してあります。
[light css ver 1](https://motimoti-dev.github.io/light-css/css/light-ver-1.css "ver 1")

## light-cssの役割
例えばmargin 0 autoのCSSを記述するときにいちいちclassを定義して書いていると時間がかかってしまうのであらかじめm-0aのようなclassを作っておいてこれをclassに打ち込んで楽しようという奴です。
ある程度簡単な命名規則でデータ量を抑えたCSSを定義しています。

## それぞれのルール
プロパティの名前と内容を「-」で区切っています。それだけです。

### margin padding

|  /  |  省略文字  |
| ---- | ---- |
|  margin  |  m  |
|  padding  |  p  |
|  auto  |  a  |
|  top  |  t  |
|  right  |  r  |
|  left  |  l  |
|  bottom  |  b  |

数字はそのまま使用します。

|  省略されたクラス名  |  内容  |
| ---- | ---- |
|  m-0  |  margin:0  |
|  m-0a  |  margin:0 auto  |
|  m_t-0  |  margin-top:0  |
|  m_r-0  |  margin-right:0  |
|  m_l-0  |  margin-left:0  |
|  m_b-0  |  margin-bottom:0  |

paddingも同じように定義されています。

### 他の細かいの

|  省略されたクラス名  |  内容  |
| ---- | ---- |
|  f-l  |  float:left  |
|  f-r  |  float:right  |
|  c-b  |  clear:both  |
|  c-p  |  cursor: pointer  |
|  pos-f  |  position:fixed  |
|  pos-r  |  position:relative  |
|  pos-a  |  position:absolute  |
|  b-12px  |  border-radius:12px  |
|  w-100  |  width:100%  |
|  h-100  |  height:100%  |
|  h-a  |  height:auto  |
|  o-h  |  overflow:hidden  |
|  o_x-s  |  overflow-x:scroll  |
|  o_y-s  |  overflow-y:scroll  |
|  o_f-c  |  object-fit:cover  |
|  f_w-b  |  font-weight:bold  |
|  t_d-n  |  text-decoration:none  |
|  w_b-b_w  |  word-break:break-word  |
|  w_b-b_a  |  word-break:break-all  |
|  t_a-r  |  text-align:right  |
|  t_a-c  |  text-align:center  |
|  t_a-l  |  text-align:left  |
|  z_i-1  |  z-index:1  |
|  z_i-9  |  z-index:99999  |
|  z_i-1  |  z-index:1  |
|  b-n  |  background:none  |
|  v_a-m  |  vertical-align:middle  |
 
### 書くのがめんどくさい系

|  省略されたクラス名  |  内容  |
| ---- | ---- |
|  b_s-1  |  box-shadow:0 2px 4px #4385bb12  |

### displayとか

|  省略されたクラス名  |  内容  |
| ---- | ---- |
|  d-u  |  display:unset  |
|  d-f  |  display:flex  |
|  j_c-s_b  |  justify-content:space-between  |
|  j_c-c  |  justify-content:center  |
|  j_c-s  |  justify-content:start  |
|  d-g  |  display:grid  |
|  a_t-c  |  align-items:center  |
|  g_t_c-n  |  grid-template-columns:none  |
|  g_t_c-1fr  |  grid-template-columns:1fr  |
|  g_t_c-1fr1fr  |  grid-template-columns:1fr 1fr  |
|  g-12px  |  gap:12px  |
|  d-b  |  display:block  |
|  d-i  |  display:inline  |
|  d-i_b  |  display:inline-block  |
|  d-n  |  display:none  |
|  d-t  |  display:table  |
|  d-t_c  |  display:table-cell  |
