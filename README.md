# Your Cat 모자 아이콘

Steam 보관함 아이템 정의(`icon_url`, `icon_url_large`)가 이 주소의 그림을 쓴다. 파일 이름이나 위치를 바꾸면 Steam 아이콘이 깨지므로 그대로 둔다.

- `hats/v3/<모자 id>.png`: 200px, `hats/v3/<모자 id>_large.png`: 512px (지금 쓰는 것. 그림 가장자리 흰 조각을 지운 판)
- `hats/v2/`: 이전 판(새 그림, 가장자리 흰 조각 있음)
- `hats/`: 처음 판

Steam은 주소별로 그림을 저장해 두므로 그림을 바꿀 때는 새 폴더(v4 등)에 올리고 JSON 주소를 바꾼다. 예전 폴더는 지우지 않는다.

원본과 생성 스크립트는 게임 저장소 `Tools/HatCatalog/clean_hat_edges.py`(가장자리 정리)와 `Tools/SteamInventory/build_itemdefs.py --icons`.
