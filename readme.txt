npx postcss styles/index.css --use postcss-import --use postcss-media-minmax --use postcss-csso --no-map --output styles/index.min.css
Данная комманда запускает локально плагин postcss, импортирует стили, преобразует их для кроссбраузерности и минифицирует

Уставливали плагин и зависимости коммандой npm install postcss-cli postcss-import postcss-media-minmax postcss-csso