# pokemoji

## Danh sách emoji Pokemon cho [emojipacks](https://github.com/GaLaiLapTrinh/pokemon)

Dễ dàng nhập tất cả 151 Pokemon gốc vào nhóm Slack của bạn!

Nhiều cảm ơn đến [PokemonGo-Map](https://github.com/AHAAAAAAA/PokemonGo-Map/) và [Pokéapi](https://pokeapi.co/).

# Tóm tắt

https://raw.githubusercontent.com/GaLaiLapTrinh/pokemon/main/pokemon-by-name.yaml

# Cài đặt

- Có [Node.js](https://nodejs.org/)

- Cài đặt [emojipacks](https://github.com/GaLaiLapTrinh/pokemon) và chạy nó trên tệp danh sách https://raw.githubusercontent.com/GaLaiLapTrinh/pokemon/main/pokemon-by-name.yaml:
  ```
  $ npm install -g emojipacks
  ...

  $ emojipacks
  Tên miền phụ của Slack: tencongtycuaban
  Địa chỉ email đăng nhập: ten.hoa.my@tencongtycuaban.com
  Mật khẩu: *********
  Đường dẫn hoặc URL của tệp Emoji yaml: https://raw.githubusercontent.com/GaLaiLapTrinh/pokemon/main/pokemon-by-name.yaml
  ```

- Chờ một lúc... 🚶☕😴💃📖

- Dán `test-by-name` hoặc `test-by-number` vào tin nhắn trực tiếp với slackbot và kiểm tra xem nó có hoạt động không!

# Tùy chọn

- Sử dụng `pokemon-by-name.yaml` để emoji được thêm bằng tên (ví dụ: `:bulbasaur:`, `:psyduck:`)
- Sử dụng `pokemon-by-number.yaml` để emoji được thêm bằng số (ví dụ: `:pokemon-1:`, `:pokemon-54:`)

# Khác

Script tạo tệp `-by-name` từ số được đính kèm để tham khảo. Tôi khuyên bạn nên tránh sử dụng nó vì nó được làm rất nhanh chóng, nhưng nếu bạn thực sự muốn thì chỉ cần `npm install && npm run gen-name-yaml`

`gen1.json` và `gen1.yaml` chứa dữ liệu thô từ Pokéapi nếu bạn muốn tìm hiểu thêm.

`test-by-name` và `test-by-number` chứa danh sách đầy đủ, theo thứ tự, dưới dạng emoji Slack sẵn sàng để sao chép-dán vào kênh để kiểm tra.

# Giấy phép

Mã nguồn thuộc tuhoc.cc

(Bản quyền tuhoc.cc)

---


# pokemoji

Pokemon emoji list for [emojipacks](https://github.com/GaLaiLapTrinh/pokemon)

Easily import all of the original 151 Pokemon to your Slack team!

Many thanks to [PokemonGo-Map](https://github.com/AHAAAAAAA/PokemonGo-Map/) and [Pokéapi](https://pokeapi.co/).

# TLDR

https://raw.githubusercontent.com/GaLaiLapTrinh/pokemon/main/pokemon-by-name.yaml

# Install

- Have [Node.js](https://nodejs.org/)

- Install [emojipacks](https://github.com/GaLaiLapTrinh/pokemon) and run it on the list file https://raw.githubusercontent.com/GaLaiLapTrinh/pokemon/main/pokemon-by-name.yaml:
  ```
  $ npm install -g emojipacks
  ...

  $ emojipacks
  Slack subdomain: yourcompanyname
  Email address login: your.fancyname@yourcompanyname.com
  Password: *********
  Path or URL of Emoji yaml file: https://raw.githubusercontent.com/GaLaiLapTrinh/pokemon/main/pokemon-by-name.yaml
  ```

- Wait a while... 🚶☕😴💃📖

- Paste `test-by-name` or `test-by-number` into a DM with slackbot and see if it worked!

# Options

- Use `pokemon-by-name.yaml` for the emoji to be added by name (eg. `:bulbasaur:`, `:psyduck:`)
- Use `pokemon-by-number.yaml` for the emoji to be added by number (eg. `:pokemon-1:`, `:pokemon-54:`)


# Misc

The script which generated the `-by-name` file from the numbers is attached for curiosity's sake. I'd suggest avoiding it, it was _very_ hastily slapped together, but if you really want to just `npm install && npm run gen-name-yaml`

`gen1.json` and `gen1.yaml` contain the raw data from Pokéapi in case you want to muck about with it.

`test-by-name` and `test-by-number` contain the full list, in order, as Slack emoji ready to copy-paste into a channel to test them.

# License

Code is tuhoc.cc

(Copyright tuhoc.cc)