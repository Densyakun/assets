# assets

- glTF 2.0 Separate (.gltf + .bin + textures) 形式
- テクスチャは同じ階層に配置
- [glTF Viewer](https://gltf.insimo.com/) に対応
- Blender 3.1.2 で作成

## railway

### track

- 長さ1mの軌条（レール）
- 原点は軌道中心、レールの頭部（車輪の踏面）、レールの始点
- Rは再現していない
- JIS E1101
- `rail-{type}-{gauge}.gltf` はローポリゴン
- `rail-{type}-{gauge}-solid.gltf` は3Dプリンター用
- `rail.png`
  - `rail-*.gltf` が使用するレールのテクスチャ
