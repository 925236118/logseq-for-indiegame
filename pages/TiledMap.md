note-type:: #note-type/godot-api

- tile_set: TileSet
	- 指定的图块集
- Rect2i get_used_rect() const
	- 返回该地图包围矩形,包围所有图层中已经使用的非空图块
	- 返回值为图块的数量