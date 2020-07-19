# ANIPLEX-CSS3
ANIPLEX  animation/CSS3
纯CSS3实现ANIPLEX动画效果

# 主要思路
字符动画和方框动画分开考虑，剩下的抠细节即可。
# 注意点
中间的方框最终style是 transform:rotateY(90deg); 这样会导致看不到该方框，所以用 class="pcov" 的 div 来代替。
