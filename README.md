各省SVG轮廓图以及南海诸岛在下方的中国地图，修改自 https://datav.aliyun.com/portal/school/atlas/area_selector。<br>
南海诸岛在右下角的SVG中国地图，修改自 https://geojson.cn/ <br>
中国地图中，每个省份的ID都是字母，对照表请参考“省份拼音对照 - 增加南海诸岛一行 - 和南海在右的SVG对应”。<br>
“省份图标 Province SVG + Prefix” 中的“Prefix”列，已经在SVG代码前增加了“data:image/svg+xml;utf8,”。<br>
相比较于度量值，好处是在有很多重复项的图标视觉对象中，可以正常显示；<br>当然缺点也是更改颜色没有度量值灵活。<br>
记得将该列的“数据类别”设置为“图像URL”。<br>

<img width="460" alt="Snipaste_2025-06-23_13-15-05" src="https://github.com/user-attachments/assets/3f11abc2-e619-475c-8a34-c365cde8a234" /><br>
<img width="275" alt="Snipaste_2025-06-23_14-35-57" src="https://github.com/user-attachments/assets/7b0406e9-e18b-4666-9979-2164d548695b" /><br>
<br>
如需更改颜色，则把fill="#1e90ff"中1e90ff替换掉即可。
