# 30DaysMapChallenge
Day1: Points

my_map = folium.Map(location=[41.457298,69.574387],zoom_start=12)

folium.Marker(location=[41.466548,69.580238],
             popup="Проспект Амира Темура/Alisher Navoi Avenue🏛️📸; город Чирчик;главная центральная улица",icon=folium.Icon(color="green",icon="landmark",prefix="fa",tooltip="Alisher Navoi Avenue")).add_to(my_map)

folium.Marker(location=[41.444334,69.555358],
              popup="Дом Офицеров Чирчикского Гарнизона/District Officers' House🫡🇺🇿;город Чирчик;дата постройки и оформления: 1956-1965 годы",icon=folium.Icon(color="blue",icon="fa-solid fa-tree",prefix="fa",tooltip="District Officers' House")).add_to(my_map)

folium.Marker(location=[41.507040,69.619312],
              popup="Чирчикский Трансформаторный завод (ЧТЗ)/Chirchiq Transformer Plant⚡️;город Чирчик;дата начала работы: 1932 год",icon=folium.Icon(color="orange",icon="bolt",prefix="fa",tooltip="ChTZ")).add_to(my_map)

my_map.save("my_map.html")

my_map